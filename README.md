# tfjs_frozen_bug
Can't predict using loaded tensorflow FrozenModel


Error message:
Uncaught (in promise) Error: new axis mask is not yet supported
    at stridedSlice_ (strided_slice.ts:66)
    at stridedSlice (operation.ts:46)
    at executeOp$13 (slice_join_executor.ts:82)
    at executeOp$16 (operation_executor.ts:77)
    at graph_executor.ts:168
    at engine.ts:156
    at e.scopedRun (engine.ts:167)
    at e.tidy (engine.ts:153)
    at e.tidy (environment.ts:186)
    at e.execute (graph_executor.ts:157)
