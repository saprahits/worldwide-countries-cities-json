# 🌏 Worldwide Countries and Cities JSON Data

This repository provides comprehensive JSON datasets for all countries and their respective cities worldwide. It serves as an open-source project for developers, data enthusiasts, or anyone needing detailed information on countries and cities. The datasets include details like country codes, capital cities, currencies, timezones, and translations, as well as the cities' geographic information.

## 📂 Files Included

1. **Countries.json** - Contains detailed information about every country worldwide.
2. **Cities.json** - Contains detailed information about all cities within each country worldwide.

## 📥 How to Use

You can download the JSON files and integrate them into your projects as needed.

### Example Structure

#### Countries.json
Below is an example entry for Afghanistan from the `Country.json` file:

```json
{
    "id": 1,
    "name": "Afghanistan",
    "iso3": "AFG",
    "iso2": "AF",
    "numeric_code": "004",
    "phone_code": "93",
    "capital": "Kabul",
    "currency": "AFN",
    "currency_name": "Afghan afghani",
    "currency_symbol": "؋",
    "tld": ".af",
    "native": "افغانستان",
    "region": "Asia",
    "subregion": "Southern Asia",
    "nationality": "Afghan",
    "timezones": [
      {
        "zoneName": "Asia/Kabul",
        "gmtOffset": 16200,
        "gmtOffsetName": "UTC+04:30",
        "abbreviation": "AFT",
        "tzName": "Afghanistan Time"
      }
    ],
    "translations": {
      "kr": "아프가니스탄",
      "pt-BR": "Afeganistão",
      "de": "Afghanistan",
      "es": "Afganistán",
      "fr": "Afghanistan",
      "ja": "アフガニスタン",
      "cn": "阿富汗",
      "ru": "Афганистан"
    },
    "latitude": "33.00000000",
    "longitude": "65.00000000",
    "emoji": "🇦🇫"
}
```

#### Cities.json
Below is an example entry for Afghanistan from the `Cities.json` file:
```json
{
    "Afghanistan": [
        {
            "name": "Ashkāsham",
            "latitude": "36.68333000",
            "longitude": "71.53333000",
            "state_name": "Badakhshan",
            "state_code": "BDS"
        },
        {
            "name": "Fayzabad",
            "latitude": "37.11664000",
            "longitude": "70.58002000",
            "state_name": "Badakhshan",
            "state_code": "BDS"
        }
    ]
}
```

The JSON contains country data, and each city is linked to its corresponding country name, such as `Afghanistan`. Based on the country name, you can retrieve the relevant city data.

## 💡 Key Features

- **Country Details:** Name, ISO codes, numeric codes, phone codes, capitals, currencies, timezones, translations, latitude/longitude, etc.
- **City Details:** Name, latitude, longitude, state name, and state code.

## 📚 Data Fields

### Countries.json
- `id`: Unique ID for each country
- `name`: Country name
- `iso3`, `iso2`: ISO codes
- `numeric_code`: Numeric country code
- `phone_code`: Country phone code
- `capital`: Capital city
- `currency`, `currency_name`, `currency_symbol`: Currency details
- `tld`: Top-level domain
- `native`: Native country name
- `region`, `subregion`: Geographical information
- `nationality`: Nationality name
- `timezones`: Timezone details
- `translations`: Translations in various languages
- `latitude`, `longitude`: Geographic coordinates
- `emoji`: Country flag

### Cities.json
- `name`: City name
- `latitude`, `longitude`: Geographic coordinates
- `state_name`: Name of the state/province
- `state_code`: State/province code

## 🔍 How to Access

- Clone the repository using:
  ```bash
  git clone https://github.com/saprahits/worldwide-countries-cities-json.git
  ```
- Alternatively, download the JSON files directly.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve the data.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌐 Author

Created and maintained by [Hitesh Sapra](https://github.com/saprahits).

## ⭐ Give a Star

If you find this project useful, please give it a ⭐ to show your support!


