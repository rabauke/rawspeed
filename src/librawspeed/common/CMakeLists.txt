FILE(GLOB SOURCES
  "Array2DRef.h"
  "ChecksumFile.cpp"
  "ChecksumFile.h"
  "Common.cpp"
  "Common.h"
  "Cpuid.cpp"
  "DefaultInitAllocatorAdaptor.h"
  "DngOpcodes.cpp"
  "DngOpcodes.h"
  "ErrorLog.cpp"
  "ErrorLog.h"
  "Memory.cpp"
  "Memory.h"
  "Mutex.h"
  "NORangesSet.h"
  "Optional.h"
  "Point.h"
  "Range.h"
  "RawImage.cpp"
  "RawImage.h"
  "RawImageDataFloat.cpp"
  "RawImageDataU16.cpp"
  "RawspeedException.h"
  "SimpleLUT.h"
  "Spline.h"
  "TableLookUp.cpp"
  "TableLookUp.h"
)

target_sources(rawspeed PRIVATE
  ${SOURCES}
)
