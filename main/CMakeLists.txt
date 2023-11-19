# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS "main.c" "http_server.c"  "protocol_examples_utils.c" "wifi_connect.c")
set(COMPONENT_ADD_INCLUDEDIRS "")

register_component()
