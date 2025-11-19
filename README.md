# Segway Ninebot Scooters Data

JSON data for Segway Ninebot electric scooter specifications, organized by series.

## Purpose

This repository aims to help developers, researchers, and scooter enthusiasts access accurate and up-to-date information about Segway Ninebot electric scooters. All data is available in JSON format and can be accessed directly via GitHub's raw file URLs for easy integration into applications, websites, or research projects.

## Data Format

Each JSON file contains comprehensive specifications including:

- **Basic Information**: ID, name, brand
- **Battery**: Capacity (Wh)
- **Motor**: Nominal and maximum power (W)
- **Performance**: Max speed (km/h), range (km), payload capacity (kg)
- **Physical**: Weight (kg), foldable design, dimensions
- **Safety**: Front and rear brake types, tire specifications, suspension
- **Protection**: IP ratings for body and battery
- **Media**: Image URL

### Example JSON Structure

```json
{
  "id": "e2_e_ii",
  "name": "Ninebot E2 E II",
  "brand": "Segway",
  "battery_capacity_wh": 220,
  "motor_power_nominal_w": 250,
  "motor_power_max_w": 450,
  "max_speed_kmh": 20,
  "max_range_km": 25,
  "max_payload_kg": 90,
  "unit_weight_kg": 16.3,
  "foldable": true,
  "front_brake": "electronic",
  "rear_brake": "drum",
  "tire_size_inch": 8.1,
  "tire_type": "solid",
  "suspension": "front",
  "ip_body": "IPX4",
  "ip_battery": "IPX6",
  "dimensions_open_mm": "1081 x 479 x 1176",
  "dimensions_folded_mm": "1081 x 479 x 545",
  "image_url": "/images/e2_e_ii.png"
}
```

## API Endpoints

All JSON files can be accessed directly via GitHub raw URLs.

Base URL format:
```
https://raw.githubusercontent.com/snoiclub/scooters.json/master/
```

**Endpoints:**

| Series | Model | Endpoint |
|--------|-------|----------|
| E2 | E2 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/e2-series/e2_e.json) |
| E2 | E2 E II | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/e2-series/e2_e_ii.json) |
| E2 | E2 Plus E II | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/e2-series/e2_plus_e_ii.json) |
| E2 | E2 Pro E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/e2-series/e2_pro_e.json) |
| E3 | E3 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/e3-series/e3_e.json) |
| E3 | E3 Pro E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/e3-series/e3_pro_e.json) |
| F2 | F2 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f2-series/f2_e.json) |
| F2 | F2 E II | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f2-series/f2_e_ii.json) |
| F2 | F2 Plus E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f2-series/f2_plus_e.json) |
| F2 | F2 Pro E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f2-series/f2_pro_e.json) |
| F2 | F2 Pro E II | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f2-series/f2_pro_e_ii.json) |
| F3 | F3 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f3-series/f3_e.json) |
| F3 | F3 Pro E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/f3-series/f3_pro_e.json) |
| GT3 | Segway GT3 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/gt3-series/segway_gt3_e.json) |
| GT3 | Segway GT3 Pro | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/gt3-series/segway_gt3_pro.json) |
| MAX | MAX G2 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/max-series/max_g2_e.json) |
| MAX | MAX G3 E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/max-series/max_g3_e.json) |
| ZT | ZT3 Pro E | [View JSON](https://raw.githubusercontent.com/snoiclub/scooters.json/master/data/zt-series/zt3_pro_e.json) |

## Images

Product images are available in the `images/` directory. Image URLs follow this format:

```
https://raw.githubusercontent.com/snoiclub/scooters.json/master/images/{model_id}.png
```

Example:
- [e2_e.png](https://raw.githubusercontent.com/snoiclub/scooters.json/master/images/e2_e.png)
- [f3_pro_e.png](https://raw.githubusercontent.com/snoiclub/scooters.json/master/images/f3_pro_e.png)

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

The specifications provided in this repository are based on official Segway Ninebot documentation and are accurate to the best of our knowledge. Always verify with official sources before making purchasing decisions. Specifications may vary by region and model year.

## Updates

This repository is maintained and updated regularly to reflect the latest Segway Ninebot scooter models and specifications.

