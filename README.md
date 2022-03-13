# Process Mining Replay technique

## The analysis of popular methods for checking conformance is presented in the [replay_it.ipynb](https://github.com/eskvortsova/replay_PM/blob/master/Replay%20it.ipynb) file:
- Footprints Conformance check
- Token-Based replay
- Alignments check

## Practically derived technique for conformance checking presented [custom_replay.ipynb](https://github.com/eskvortsova/replay_PM/blob/master/Custom%20Replay.ipynb):
The main idea behind this method is overlay of two DFGs and the presence of visualization, which clearly shows the number of traces in which several actions were missed.
This method has been developed for the needs of a particular customer for practical reasons, it does not rely on scientific articles.
