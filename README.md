Grid-Engine-Prolog-Scripts
==========================

Some prolog/epilog Scripts we use with   Grid engine on our cluster.
This includes the scripts for locking/allocating GPU written by Andreas Roussos 
and the infrastructure for faking a parallel prolog/epilog and calling subscripts written by me.
Note that these are copies from our working system and were not designed to be release quality.
1)Hard coded paths
2)Somewhat depends on aspects of our system.  In particular our JSV (not included) sets an environment variable used by the GPU scripts.
3)Non-standard lock file location.
4)Hard coded for 2 GPUs

All copyright UCL
