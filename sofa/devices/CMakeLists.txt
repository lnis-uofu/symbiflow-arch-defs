add_subdirectory(k4_N8)

define_device(
  DEVICE sofa_device
  ARCH sofa
  DEVICE_TYPE k4_N8
  PACKAGES dummy
  CACHE_ARGS --route_chan_width 100
  )
