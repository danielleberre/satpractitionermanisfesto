# The SAT Practitioner Manisfesto

Practical SAT research is both time and resource consuming.
As such, it is important that the community provides some
guidelines to make sure that all efforts made by practitioners
are properly recognized during paper evaluation.

The following principles are adopted by the community.

1. Benchmarks should be available for research purposes.
1. Solvers should be available in binary form for research purposes.
1. Experimental results should include comparison with the state of the art.
1. Experimental conditions details should be provided (hardware, OS).
1. Generic benchmarks sets (e.g. competition benchmarks) can be used during a period of 3 years.


## Benchmarks should be publicly available for research purpose

Papers presenting results on benchmarks should provide a link to those benchmarks,
preferably the raw benchmarks, else a generator for those benchmarks.

In general, the community is also interested on results that improve SAT solving on
non-public benchmarks. Still authors are expected to make their research repeatable
and extensible by others, by providing for instance artificial but public benchmarks,
with similar characteristics, on which the new methods is also evaluated.

## Solvers should be available in binary form for research purpose

Papers presenting experimental results about a system (solver) should
allow the community to access this solver in at least binary form,
preferably in source form. This allows to check performance claims independently.

## Experimental results should include comparison with the state-of-the-art

The community has established regular competitive events to publicly promote state-of-the art systems.
It is expected that experimental results, about benchmarks or solvers, includes state-of-the-art 
systems highlighted during recent competitive events. The comparison could also include
reference systems (widely used systems which might no longer be considered as state-of-the-art).

In order to better understand the contribution to the state-of-the-art, and since competition results
provide a large resource of independent experiments, is also advisable to include a comparison to
top performing solvers of one of the last competitive events on exactly the benchmarks of this event.

>  Many papers report results on arbitrarily merge benchmarks and then only
> report results on those.  Then one can not check out other papers (or competition results),
> to figure out what this really means (without running the competition again on the benchmarks).
> It is better to use a canonical set of benchmarks, for which the community already has numbers.  So using
> only 2018, 2019, 2020 benchmarks alone make sense, but not merging them (or some pairs)
> and ONLY reporting on the merged instance set. The point is that a reader can compare the results with existing results without the
> need to run something (or do some complicated spreadsheet hack).

Beside reporting on the number of solved instances or run-time (including PAR2 scores etc.) it is most
instructive to also include secondary statistics.  For instance if a new method is supposed
to reduce the number of conflicts, then of course the number of needed conflicts should be included.

## Experimental conditions details should be provided (hardware, OS)

The experimental results much depend on the hardware (CPU, amount of RAM, L2/L3 cache, NUMA architecture, etc.) and operating system.
Those details should be provided when reporting the results.

## Generic benchmarks sets (e.g. competition benchmarks) can be used during a period of 3 years

It takes time and computer resources to collect empirical evidences and to dig details about benchmarks sets.
All data retrieved on a set of benchmarks from competitive event year X should not be void as soon as a 
new set of benchmarks is unveiled.
As such, the community acknowledge that benchmarks set from year X can be used as a reference until year X+3 included.

