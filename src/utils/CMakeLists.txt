add_library(utility blob.cpp deserializer.cpp id_context.cpp id_placeholder.cpp identifiable.cpp 
object_data.cpp property.cpp property_container.cpp property_container_manager.cpp property_eigen.cpp
property_identifiable.cpp serializable.cpp serialization_context.cpp serializer.cpp)
target_include_directories(utility PRIVATE ${CMAKE_SOURCE_DIR}/src)
target_include_directories(utility PRIVATE ${EIGEN3_INCLUDE_DIR})