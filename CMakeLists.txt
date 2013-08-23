add_executable (wrap-addin
  c_g1awrapper.c
  bmp_utils.c
)

install (TARGETS wrap-addin
  RUNTIME DESTINATION bin)
