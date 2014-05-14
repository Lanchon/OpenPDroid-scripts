OpenPDroid-scripts
==================

Scripts to make and apply OpenPDroid framework patches.


Installation
------------

Configure paths in 'opd-set-env'.


Usage
-----

* opd-apply: apply patches to the affected components of the framework
* opd-diff-apply: apply patches and diff the output to a prior reference output to only show novelties
* opd-reset: remove patches by reseting the affected components from the local repos
* opd-remove-intermediates: delete previously built target files of the affected components
* opd-make-patches: create patches for the affected components from the live framework tree
