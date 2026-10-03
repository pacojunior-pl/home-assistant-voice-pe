# Rejestracja komponentu i jawne wskazanie zależności od wbudowanego klienta WebSocket
idf_component_register(SRCS "gemini_proxy.cpp"
                       REQUIRES esp_websocket_client)
