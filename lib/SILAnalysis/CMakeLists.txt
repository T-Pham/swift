add_swift_library(swiftSILAnalysis
  ARCAnalysis.cpp
  AliasAnalysis.cpp
  Analysis.cpp
  ArraySemantic.cpp
  BasicCalleeAnalysis.cpp
  CFG.cpp
  CallGraph.cpp
  ClassHierarchyAnalysis.cpp
  ColdBlockInfo.cpp
  DestructorAnalysis.cpp
  EscapeAnalysis.cpp
  FunctionOrder.cpp
  IVAnalysis.cpp
  LoopAnalysis.cpp
  LoopRegionAnalysis.cpp
  MemoryBehavior.cpp
  RCIdentityAnalysis.cpp
  SideEffectAnalysis.cpp
  SimplifyInstruction.cpp
  ValueTracking.cpp
  LINK_LIBRARIES swiftSILPassesUtils)
