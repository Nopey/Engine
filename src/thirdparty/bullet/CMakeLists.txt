#
# We will fix up Bullet definitions here
#

add_definitions(-DMBCS)

add_subdirectory(src/BulletCollision)
add_subdirectory(src/BulletDynamics)
add_subdirectory(src/BulletMultiThreaded)
add_subdirectory(src/BulletSoftBody)
add_subdirectory(src/LinearMath)
