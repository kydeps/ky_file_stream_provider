find_package(glog)

add_library(ky_file_stream_provider file_stream_provider.cc)
target_link_libraries(ky_file_stream_provider PRIVATE glog::glog)
KyDepsPackageLibraryTarget(ky_file_stream_provider "ky")
