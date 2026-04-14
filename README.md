# Changan Lumin - EV Charging Calculator ⚡🚗

A modern, web-based calculator designed specifically for **Changan Lumin** owners. This tool helps estimate the charging time and total electricity cost based on the current battery level, charger power, and electricity rate.

![Changan Lumin](https://img.shields.io/badge/Changan-Lumin-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **Dark Mode UI**: A sleek, modern interface styled with Tailwind CSS.
- **Dynamic Updates**: Real-time calculations as you adjust the slider or input fields.
- **Model Specific Logic**:
  - **Lumin L (รุ่นปกติ / AC)**: Limits AC charging speed to maximum 3.3 kW. Flags DC charging as unsupported.
  - **Lumin L DC (รองรับชาร์จเร็ว)**: Limits AC charging to 3.3 kW and allows DC Fast Charging up to 30 kW.
- **Smart Validation**: Shows helpful warnings when input power exceeds the vehicle's onboard charger limits.
- **Cost Estimation**: Provides clear breakdowns of electricity costs both **Before VAT** and **Including 7% VAT**.
- **User Guide & Reference**: Includes a dedicated `howto.html` page detailing usage instructions, tips for checking station power, and technical charging specifications for the Changan Lumin Series.
## 🚀 How to Use

Since this is a client-side (frontend-only) application, there is no complicated setup required!

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Safari, Edge, Firefox).
3. Select your **Car Model** and **Charger Type** (AC/DC).
4. Move the **Battery Slider** to match your car's current State of Charge (SoC).
5. Input the **Charger Power (kW)** and **Power Rate (THB/kWh)** as displayed at your charging station.
6. The cards for **80%** and **100%** targets will instantly update with the recommended waiting time and total cost.

## 🛠 Tech Stack

- **HTML5**: semantic structure
- **Tailwind CSS (via CDN)**: styling, layout, dark-mode colors, and responsive design
- **Vanilla JavaScript**: DOM manipulation and calculation logic

## 📂 Project Structure

```text
📦 LuminChargeCalculator
 ┣ 📜 index.html    # The main calculator application
 ┣ 📜 howto.html    # User manual and reference specifications page
 ┗ 📜 README.md     # Project documentation
```

## 🤝 Contribution

Feel free to fork this repository, make changes, and submit pull requests. If you have any suggestions or find bugs, please open an issue.

- **Contributed by:** Abdulloh Etaeluengoh
- **Email:** Abdulloh.eg@gmail.com
