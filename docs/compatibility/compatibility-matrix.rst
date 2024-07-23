.. meta::
    :description: ROCm compatibility matrix
    :keywords: AMD, GPU, architecture, hardware, compatibility, requirements

**************************************************************************************
Compatibility matrix
**************************************************************************************

Use this matrix to view the ROCm compatibility across successive major and minor releases.


.. container:: format-big-table

  .. csv-table:: 
      :header: "ROCm Version", "6.1.0", "6.0.0"
      :stub-columns: 1

      :doc:`Operating Systems <rocm-install-on-linux:reference/system-requirements>`, "Ubuntu 22.04.4, 22.04.3","Ubuntu 22.04.4, 22.04.3"
      ,"Ubuntu 20.04.6, 20.04.5","Ubuntu 20.04.6, 20.04.5"
      ,"RHEL 9.4 [#red-hat94]_, 9.3, 9.2","RHEL 9.3, 9.2"
      ,"RHEL 8.9, 8.8","RHEL 8.9, 8.8"
      ,"SLES 15 SP5, SP4","SLES 15 SP5, SP4"
      ,CentOS 7.9,CentOS 7.9
      ,"Oracle Linux 8.9 [#oracle89]_"
      ,,
      :doc:`GFX Architecture <rocm-install-on-linux:reference/system-requirements>`,CDNA3,CDNA3
      ,CDNA2,CDNA2
      ,CDNA,CDNA
      ,RDNA3,RDNA3
      ,RDNA2,RDNA2
      ,,
      :doc:`GFX Card <rocm-install-on-linux:reference/system-requirements>`,gfx1100,gfx1100
      ,gfx1030,gfx1030
      ,gfx942 [#]_, gfx942 [#]_
      ,gfx90a,gfx90a
      ,gfx908,gfx908
      ,,
      ECOSYSTEM SUPPORT:,,
      :doc:`PyTorch <rocm-install-on-linux:how-to/3rd-party/pytorch-install>`,"2.1, 2.0, 1.13","2.1, 2.0, 1.13"
      :doc:`TensorFlow <rocm-install-on-linux:how-to/3rd-party/tensorflow-install>`,"2.15, 2.14, 2.13","2.14, 2.13, 2.12"
      :doc:`JAX <rocm-install-on-linux:how-to/3rd-party/jax-install>`,0.4.26,0.4.26
      `ONNX Runtime <https://onnxruntime.ai/docs/build/eps.html#amd-migraphx>`_,1.17.3,1.14.1
      ,,
      3RD PARTY COMMUNICATION LIBS:,,
      `UCC <https://github.com/ROCm/ucc>`_,>=1.2.0,>=1.2.0
      `UCX <https://github.com/ROCm/ucx>`_,>=1.14.1,>=1.14.1
      ,,
      3RD PARTY ALGORITHM LIBS:,,
      Thrust,2.1.0,2.0.1
      CUB,2.1.0,2.0.1
      ,,
      ML & COMPUTER VISION LIBS:,,
      :doc:`Composable Kernel <composable_kernel:index>`,1.1.0,1.1.0
      :doc:`MIGraphX <amdmigraphx:index>`,2.9.0,2.8.0
      :doc:`MIOpen <miopen:index>`,3.1.0,3.0.0
      :doc:`MIVisionX <mivisionx:index>`,2.5.0,2.5.0
      :doc:`rocDecode <rocdecode:index>`,0.5.0,N/A
      :doc:`ROCm Performance Primitives (RPP) <rpp:index>`,1.5.0,1.4.0
      ,,
      COMMUNICATION:,,
      :doc:`RCCL <rccl:index>`,2.18.6,2.18.3
      ,,
      MATH LIBS:,,
      `half <https://github.com/ROCm/half>`_ ,1.12.0,1.12.0
      :doc:`hipBLAS <hipblas:index>`,2.1.0,2.0.0
      :doc:`hipBLASLt <hipblaslt:index>`,0.7.0,0.6.0
      :doc:`hipFFT <hipfft:index>`,1.0.14,1.0.13
      :doc:`hipFORT <hipfort:index>`,0.4.0,0.4.0
      :doc:`hipRAND <hiprand:index>`,2.10.16,2.10.16
      :doc:`hipSOLVER <hipsolver:index>`,2.1.0,2.0.0
      :doc:`hipSPARSE <hipsparse:index>`,3.0.1,3.0.0
      :doc:`hipSPARSELt <hipsparselt:index>`,0.1.0,0.1.0
      :doc:`rocALUTION <rocalution:index>`,3.1.1,3.0.3
      :doc:`rocBLAS <rocblas:index>`,4.1.0,4.0.0
      :doc:`rocFFT <rocfft:index>`,1.0.27,1.0.23
      :doc:`rocRAND <rocrand:index>`,3.0.1,2.10.17
      :doc:`rocSOLVER <rocsolver:index>`,3.25.0,3.24.0
      :doc:`rocSPARSE <rocsparse:index>`,3.1.2,3.0.2
      :doc:`rocWMMA <rocwmma:index>`,1.4.0,1.3.0
      `Tensile <https://github.com/ROCm/Tensile>`_,4.40.0,4.39.0
      ,,
      PRIMITIVES:,,
      :doc:`hipCUB <hipcub:index>`,3.1.0,3.0.0
      :doc:`hipTensor <hiptensor:index>`,1.2.0,1.1.0
      :doc:`rocPRIM <rocprim:index>`,3.1.0,3.0.0
      :doc:`rocThrust <rocthrust:index>`,3.0.1,3.0.0
      ,,
      SUPPORT LIBS:,,
      `hipother <https://github.com/ROCm/hipother>`_,6.1.40091,6.0.32830
      :doc:`ROCm CMake <rocmcmakebuildtools:index>`,0.12.0,0.11.0
      `rocm-core <https://github.com/ROCm/rocm-core>`_,6.1.0,6.0.0
      `ROCT-Thunk-Interface <https://github.com/ROCm/ROCT-Thunk-Interface>`_,20240125.3.30,20231016.2.245
      ,,
      TOOLS:,,
      :doc:`AMD SMI <amdsmi:index>`,24.4.1,23.4.2
      :doc:`HIPIFY <hipify:index>`,17.0.0,17.0.0
      :doc:`ROCdbgapi <rocdbgapi:index>`,0.71.0,0.71.0
      :doc:`rocminfo <rocminfo:index>`,1.0.0,1.0.0
      :doc:`ROCProfiler <rocprofiler:index>`,2.0.60100,2.0.0
      `rocprofiler-register <https://github.com/ROCm/rocprofiler-register>`_,0.3.0,N/A
      :doc:`ROCTracer <roctracer:index>`,4.1.60100,4.1.0
      :doc:`ROCm Bandwidth Test <rocm_bandwidth_test:index>`,1.4.0,1.4.0
      :doc:`ROCm Data Center Tool <rdc:index>`,0.3.0,0.3.0
      :doc:`ROCm Debugger (ROCgdb) <rocgdb:index>`,14.1.0,13.2.0
      :doc:`ROCm SMI <rocm_smi_lib:index>`,7.0.0,6.0.0
      :doc:`ROCm Validation Suite <rocmvalidationsuite:index>`,rocm-6.1.0,rocm-6.0.0
      :doc:`ROCr Debug Agent <rocr_debug_agent:index>`,2.0.3,2.0.3
      :doc:`TransferBench <transferbench:index>`,1.48,1.46
      ,,
      COMPILERS:,,
      `clang-ocl <https://github.com/ROCm/clang-ocl>`_,0.5.0,0.5.0
      `Flang <https://github.com/ROCm/flang>`_,17.0.0.24103,17.0.0.23483
      `llvm-project <https://github.com/ROCm/llvm-project>`_,17.0.0.24103,17.0.0.23483
      `OpenMP <https://github.com/ROCm/llvm-project/tree/amd-staging/openmp>`_,17.0.0.24103,17.0.0.23483
      ,,
      RUNTIMES:,,
      :doc:`HIP <hip:index>`,6.1.40091,6.0.32830
      `OpenCL Runtime <https://github.com/ROCm/clr/tree/develop/opencl>`_,2.0.0,2.0.0
      :doc:`ROCR-Runtime <rocr-runtime:index>`,1.13.0,1.12.0


.. rubric:: Footnotes

.. [#red-hat94] **For ROCm 6.1** - RHEL 9.4 is supported only on AMD Instinct MI300A.
.. [#oracle89] **For ROCm 6.1.1** - Oracle Linux is supported only on AMD Instinct MI300X.
.. [#] **For ROCm 6.1** - MI300A (gfx942) is supported on Ubuntu 22.04.4, RHEL 9.4, RHEL 9.3, RHEL 8.9, and SLES 15 SP5. MI300X (gfx942) is only supported on Ubuntu 22.04.4.
.. [#] **For ROCm 6.0** - MI300A (gfx942) is supported on Ubuntu 22.04.3, RHEL 8.9 and SLES 15 SP5. MI300X (gfx942) is only supported on Ubuntu 22.04.3.

