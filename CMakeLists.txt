# Copyright (C) 2007-2012 LuaDist.
# Submitted by David Manura
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( bin2clua )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

# Install
install_lua_executable ( bin2c bin2c )
install_data ( COPYRIGHT )
