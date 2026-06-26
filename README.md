````markdown
# 🏊 Basen Timer Plug

**Basen Timer Plug** to lokalny sterownik czasowy oparty na **ESPHome** dla urządzeń z **ESP8266** i **ESP32**.

Projekt powstał z myślą o automatycznym sterowaniu urządzeniami wymagającymi pracy cyklicznej, np.:

- 🏊 pompy basenowej
- 🌬️ wentylatora
- 💨 kompresora
- 💡 oświetlenia
- 🚰 pompki
- ⚙️ innych urządzeń zasilanych przez przekaźnik

Urządzenie działa **całkowicie lokalnie**. Nie wymaga Home Assistanta ani dostępu do Internetu.

Jeżeli Home Assistant jest dostępny, urządzenie automatycznie udostępnia wszystkie encje przez ESPHome API.

---

# Funkcje

- ✅ Cykliczna praca ON/OFF
- ✅ Konfigurowany czas ON
- ✅ Konfigurowany czas OFF
- ✅ Harmonogram godzin pracy
- ✅ Automatyczne wyłączenie poza harmonogramem
- ✅ Sterowanie z poziomu strony WWW
- ✅ Integracja z Home Assistant
- ✅ OTA (aktualizacja przez WiFi)
- ✅ Zapamiętywanie ustawień po zaniku zasilania

---

# Obsługiwane urządzenia

Obecnie projekt jest przygotowany dla:

- Sonoff S26
- AIS Dom S26

W przyszłości planowane jest wsparcie dla:

- Sonoff Basic
- Sonoff Mini
- ESP8266
- ESP32
- innych urządzeń opartych o ESPHome

---

# Wymagania

- ESPHome
- ESP8266 lub ESP32
- sieć WiFi 2.4 GHz

---

# Instalacja

1. Sklonuj repozytorium.

```bash
git clone https://github.com/pimowo/Basen-Timer-Plug.git
````

2. Otwórz plik:

```
basen-timer-plug.yaml
```

3. Uzupełnij dane WiFi.

4. Skompiluj projekt w ESPHome.

5. Wgraj firmware.

---

# Konfiguracja

Parametry dostępne z poziomu WWW:

* ON Time
* OFF Time
* Start Hour
* Start Minute
* Stop Hour
* Stop Minute
* Auto Cycle

---

# Plan rozwoju

## v0.2

* Cykliczna praca ON/OFF

## v0.3

* Harmonogram godzin

## v0.4

* Licznik cykli
* Pozostały czas

## v1.0

* Stabilne wydanie

---

# Licencja

Projekt udostępniony na licencji MIT.

Szczegóły znajdują się w pliku LICENSE.

```
```
