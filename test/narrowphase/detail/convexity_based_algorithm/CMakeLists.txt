set(tests
    test_gjk_libccd-inl.cpp
    test_gjk_libccd-inl_extractClosestPoints.cpp
)

# Build all the tests
foreach(test ${tests})
  add_fcl_test(${test})
endforeach(test)
