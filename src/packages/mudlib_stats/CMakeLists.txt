option(PACKAGE_MUDLIB_STATS "mudlib_stats package" ON)

if(${PACKAGE_MUDLIB_STATS})
    add_library(package_mudlib_stats STATIC
            "mudlib_stats.cc"
            "mudlib_stats.h"
            )
endif()
