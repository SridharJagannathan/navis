.. _whats_new:

What's new?
===========

.. list-table::
   :widths: 7 7 86
   :header-rows: 1

   * - Version
     - Date
     -
   * - 0.1.17
     - 29/06/20
     - - new :class:`~navis.TreeNeuron` property ``.volume``
       - we now use `ncollpyde <https://pypi.org/project/ncollpyde>`_ for ray casting (intersections)
       - clean-up in neuromorpho interface
       - fix bugs in :class:`~navis.Volume` pickling
   * - 0.1.16
     - 26/05/20
     - - many small bugfixes
   * - 0.1.15
     - 15/05/20
     - - improvements to R and Blender interface
       - improved loading from SWCs (up to 2x faster)
       - TreeNeurons: allow rerooting by setting the ``.root`` attribute
   * - 0.1.14
     - 05/05/20
     - - emergency fixes for 0.1.13
   * - 0.1.13
     - 05/05/20
     - - new function :func:`navis.vary_color`
       - improvements to Blender interface and various other functions
   * - 0.1.12
     - 02/04/20
     - - :class:`~navis.Volume` is now sublcass of ``trimesh.Trimesh``
   * - 0.1.11
     - 28/02/20
     - - removed hard-coded swapping and translation of axes in the Blender interface
       - improved :func:`navis.stitch_neurons`: much faster now if you have iGraph
       - fixed errors when using multiprocessing (e.g. in ``NeuronList.apply``)
       - fixed bugs in :func:`navis.downsample_neuron`
   * - 0.1.10
     - 24/02/20
     - - fixed bugs in Blender interface introduced in 0.1.9
   * - 0.1.9
     - 24/02/20
     - - removed hard-coded swapping and translation of axes in the Blender interface
       - fixed bugs in stitch_neurons
   * - 0.1.8
     - 21/02/20
     - - Again lots of fixed bugs
       - Blame myself for not keeping track of changes
   * - 0.1.0
     - 23/05/19
     - - Made lots of fixes
       - Promised myself to be better at tracking changes
   * - 0.0.1
     - 29/01/19
     - - First commit, lots to fix.
