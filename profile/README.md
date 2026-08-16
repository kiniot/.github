<p align="center">
  <img src="../assets/uflex/logo-uflex.svg" alt="uFlex" width="360">
</p>

<h1 align="center">Connected rehabilitation, from movement to clinical insight</h1>

<p align="center">
  KinIoT builds <b>uFlex</b>, an IoT telerehabilitation ecosystem that connects wearable motion sensors, edge computing, clinical workflows, and guided patient therapy.
</p>

<p align="center">
  <a href="https://uflex-landing-page.vercel.app/"><b>Explore uFlex</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://uflex-clinic-web.vercel.app/sign-in?demo=1"><b>Open the interactive demo</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active_Development-48CBB6?style=flat-square" alt="Status: active development">
  <img src="https://img.shields.io/badge/Focus-HealthTech-00566B?style=flat-square" alt="Focus: HealthTech">
  <img src="https://img.shields.io/badge/Origin-UPC-C8102E?style=flat-square" alt="Origin: UPC">
</p>

<p align="center">
  <img src="../assets/uflex/landing-hero.png" alt="uFlex connected rehabilitation platform" width="900">
</p>

## About KinIoT

We are a software and IoT team founded by Software Engineering students at **UPC** in Lima, Peru. We created uFlex to bring measurable, supervised rehabilitation into the home while keeping physiotherapists connected to each patient's progress.

## One connected rehabilitation ecosystem

uFlex follows movement across the complete care loop:

**ESP32 wearable → Edge Gateway → REST API → Clinic & Developer Web + Patient Mobile**

- The wearable kit measures joint motion through multiple inertial sensors and provides immediate safety feedback.
- The Edge Gateway turns high-frequency sensor readings into reliable local and cloud-ready therapy data.
- The REST API coordinates identity, clinics, treatment plans, devices, sessions, and platform operations.
- Clinic teams plan therapy and review measurable outcomes, while patients follow guided exercises from the mobile app.

## uFlex in action

### Clinical planning and progress

![Physiotherapist dashboard with treatment and patient progress](../assets/uflex/clinic-dashboard.png)

Physiotherapists can coordinate active treatment plans, monitor adherence, and inspect rehabilitation progress from a role-focused clinical workspace.

### Guided therapy with connected hardware

<table>
  <tr>
    <td width="38%" align="center"><img src="../assets/uflex/patient-device-connected.png" alt="uFlex patient app connected to the sensor kit" width="330"></td>
    <td width="62%" align="center"><img src="../assets/uflex/hardware-overview.jpg" alt="uFlex wearable sensor hardware" width="520"></td>
  </tr>
  <tr>
    <td align="center"><sub>Patient app pairing and sensor readiness</sub></td>
    <td align="center"><sub>ESP32-based wearable prototype with three inertial sensing points</sub></td>
  </tr>
</table>

## Project ecosystem

| Repository | Role in uFlex | Tech stack |
|:--|:--|:--|
| [**uflex-landing-page**](https://github.com/KinIoT/uflex-landing-page) | Product story, benefits, technology, and plans. | Vite · Tailwind CSS · DaisyUI |
| [**uflex-clinic-web**](https://github.com/KinIoT/uflex-clinic-web) | Clinical workspace for administrators and physiotherapists. | Angular · TypeScript · PrimeNG |
| [**uflex-patient-mobile**](https://github.com/KinIoT/uflex-patient-mobile) | Guided Android rehabilitation and live kit feedback. | Kotlin · Jetpack Compose |
| [**uflex-developer-web**](https://github.com/KinIoT/uflex-developer-web) | Internal fleet, inventory, fulfillment, and gateway operations. | React · Vite · shadcn/ui |
| [**uflex-rest-api**](https://github.com/KinIoT/uflex-rest-api) | Core business capabilities and ecosystem integration. | Java · Spring Boot · PostgreSQL |
| [**uflex-edge-gateway**](https://github.com/KinIoT/uflex-edge-gateway) | Local therapy context, movement processing, and reliable synchronization. | Python · Flask |
| [**uflex-embedded-app**](https://github.com/KinIoT/uflex-embedded-app) | Wearable sensing, motion calculation, and local safety feedback. | C++ · ESP32 · PlatformIO |
| [**uflex-final-report**](https://github.com/KinIoT/uflex-final-report) | Academic and architectural documentation for the complete project. | Markdown · Documentation |

> [!TIP]
> Start with the [live landing page](https://uflex-landing-page.vercel.app/) or enter the [Clinic Web demo](https://uflex-clinic-web.vercel.app/sign-in?demo=1) without creating an account.

## Get in touch

- **Organization:** [KinIoT on GitHub](https://github.com/KinIoT)
- **Location:** Lima, Peru 🇵🇪
