#this file is automatically generated 
if(PKGCONFIG_FOUND)
    pkg_check_modules(FREETYPE freetype2)
    link_directories("${FREETYPE_LIBRARY_DIRS}")
endif()

SET(TARGET_SRC osglazyrender.cpp )
SET(TARGET_ADDED_LIBRARIES osgStupeflix )
#### end var setup  ###
SETUP_EXAMPLE(osglazyrender)
