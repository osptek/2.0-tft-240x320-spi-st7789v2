# 2.0" 240×320 TFT SPI module (ST7789V2) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides an **ESP-IDF sample project**. Datasheets and specifications will be added to `docs/` when available.

## Product overview

| Item | Description |
|:--|:--|
| Module | 2.0-inch **TFT** (IPS), **240×320** resolution |
| Interface | **SPI** |
| Driver IC | **ST7789V2** |
| Spec ID | **`2.0-tft-240x320-spi-st7789v2`** is the common product designation in documentation |
| Other 2.0″ variants | **460×460 AMOLED**: **`2.0-amoled-460x460-qspi-co5300`**, **`2.0-amoled-460x460-mipi-co5300`** — separate repos |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `assets/` | Demo screenshots for sample projects (when available) |
| `docs/` | Datasheets and specifications (**to be added**) |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description |
|:--|:--|
| `examples/` root | ESP32-S3 + IDF5: ST7789V2 SPI + LVGL9 (heart-rate chart UI demo) |

### Sample project paths

| Description | Path |
|:--|:--|
| ST7789V2 SPI bringup (LVGL9) | `examples/esp32s3-2.0-tft-240x320-spi-st7789v2-bringup/` |
