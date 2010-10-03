# Copyright (C) 2007-2010 LuaDist.
# Submitted by David Manura
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT ( bin2clua )
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(dist.cmake )

# Install
INSTALL ( PROGRAMS bin2c DESTINATION ${INSTALL_BIN} )
INSTALL ( FILES COPYRIGHT DESTINATION ${INSTALL_DATA} )


