ttk_add_base_library(trackingFromFields
  SOURCES
    TrackingFromFields.cpp
  HEADERS
    TrackingFromFields.h
  DEPENDS
    persistenceDiagram
    bottleneckDistance
    trackingFromPersistenceDiagrams
    triangulation
    )
