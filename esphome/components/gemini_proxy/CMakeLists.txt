# Prawidłowa rejestracja pojedynczego komponentu w strukturze ESPHome
idf_component_register(SRCS "gemini_proxy.cpp"
                       REQUIRES esp_websocket_client)
