# To jest jedyna i w 100% bezpieczna metoda rejestracji biblioteki WebSocket w ESP-IDF
idf_component_register(SRCS "gemini_proxy.cpp"
                       REQUIRES esp_websocket_client)
