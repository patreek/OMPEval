add_library(OMPEval STATIC omp/CardRange.cpp omp/CombinedRange.cpp omp/EquityCalculator.cpp omp/HandEvaluator.cpp)
target_compile_options(OMPEval PRIVATE -fPIC)