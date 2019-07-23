###################################################################################
#                                                                                 #
# NAME: src/main/meson.build                                                      #
#                                                                                 #
# AUTHOR: Michael Brockus.                                                        #
#                                                                                 #
# CONTACT: <mailto:michael@squidfarts.com>                                        #
#                                                                                 #
# NOTICES:                                                                        #
#                                                                                 #
# License: MIT                                                                    #
#                                                                                 #
###################################################################################



exe_src = [ 'main.kt' ]



custom_target('exe',
    output : 'MainKt.jar',
    input : exe_src,
    command : ['kotlinc', '@INPUT@', '-include-runtime', '-d', '@OUTPUT@'],
    build_by_default: true)