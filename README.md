# Macroalgal exponential decay dataset
This global dataset compiles all records of the exponential decay constant *k* for macroalgae. `k.csv` contains all data which I compiled from reviews of *k* in

- Enríquez S, Duarte CM, Sand-Jensen K (1993) Patterns in decomposition rates among photosynthetic organisms: the importance of detritus C:N:P content. *Oecologia* 94:457–471. https://doi.org/10.1007/bf00566960.
- Cebrián J, Lartigue J (2004) Patterns of herbivory and decomposition in aquatic and terrestrial ecosystems. *Ecological Monographs* 74:237–259. https://doi.org/10.1890/03-4019.
- Filbee-Dexter K, Pessarrodona A, Pedersen MF, Wernberg T, Duarte CM, Assis J, Bekkby T, Burrows MT, Carlson DF, Gattuso J-P (2024) Carbon export from seaweed forests to deep ocean sinks. *Nature Geoscience* 17:552–559. https://doi.org/10.1038/s41561-024-01449-7.
- Kennedy JR, Blain CO (2025) A systematic review of marine macroalgal degradation: toward a better understanding of macroalgal carbon sequestration potential. *Journal of Phycology* 61:399–432. https://doi.org/10.1111/jpy.70031.
- White LJ, Norkko A (2025) A path towards appropriate degradation experiments for assessing carbon sequestration potential of macroalgae. *Journal of Ecology* 113:2730–2743. https://doi.org/10.1111/1365-2745.70107.

and an unpublished review of mine using unconstrained nonlinear least squares maximum likelihood estimation to derive *k* in f(*t*) = exp(−*k**t*). I did not deem it necessary to compile a bibliography because all sources can be accessed via the respective reviews and the `DOI_original` variable. The data are structured into these variables:

- `Review` Review citation
- `DOI` Digital object identifier for review
- `Data` URL to access data
- `Reference` Citation for reference within review
- `DOI_original` Digital object identifier for reference within review
- `Order`, `Species` Latest taxonomy according to AlgaeBase (https://www.algaebase.org)
- `Kelp` Binary classifier of kelp (Laminariales and other brown seaweeds referred to as kelps)
- `Wrack` Binary classifier of beachcast/stranded/supralittoral decomposition
- `Dissolved` Binary classifier of dissolved versus particulate decomposition
- `Smallscale` Binary classifier of experimental scale
- `Prekilled` Binary classifier of pre-treatment removing detrital physiology
- `Buried` Binary classifier of burial in sediment
- `Anoxic` Binary classifier of anoxia and anaerobic decomposition
- `Lab` Binary classifier of laboratory versus field experiments
- `Darkness` Binary classifier of complete darkness during decomposition
- `k` Exponential decay constant *k* (per day)

Luka Seamus Wright, 7th January 2026
