# Pobieramy aktualną listę wymagań i dopisujemy do niej klienta WebSocket oraz bezpieczne TLS
set(REQUIRES ${REQUIRES} esp_websocket_client esp_tls json)

# Rejestrujemy komponent z zachowaniem pełnego drzewa zależności ESPHome
idf_component_register(SRCS "gemini_proxy.cpp"
                       REQUIRES ${REQUIRES})
