![GitHub's Green Software Directory](https://github.blog/wp-content/uploads/2024/09/1200x630-GHNonprofits_BlogB.png?w=1600)

---
## GitHub's Green Software Directory is a simple and easy-to-use resource that all developers can use to adopt green software tools. This list aims to help any developer find green software projects available on GitHub. 

### What is “Green Software”?
Green software meets all of our modern needs while being carbon aware and efficient. Only three activities reduce the carbon emissions of software: energy efficiency, carbon awareness, and hardware efficiency.

As technology industry energy use grows, we believe we have a responsibility to help support sustainable practices and reduce the environmental impact of software we build.

![Graph titled "Changes emerging across the climate system," which shows indicators like carbon dioxide increasing, ocean warming, and sea level rising over time.](climateindicators.jpeg)
Image source: Open access [climate visuals](https://github.com/ed-hawkins/climate-visuals) on GitHub from Ed Hawkins.

## Our Directory
We reviewed all repositories on GitHub that self-identified being green software tools as their primary purpose. We compiled these into a directory of resources built by our community, for our community. 

We were particularly inspired by the Green Software Foundation's [awesome-green-software](https://github.com/green-software-foundation/awesome-green-software) list, a valuable resource that has been developed by the Green Software Foundation community over the past few years, and the [Open Sustainable Technology](https://github.com/protontypes/open-sustainable-technology) directory. 

This list is managed by GitHub Sustainability with the Social Impact Team.

**Categories:**
- **[Measurement](#measurement)**
- **[Carbon Efficiency](#carbon-efficiency)**
- **[Carbon Awareness](#carbon-awareness)**
- **[Special Tools](#special-tools)**

Do you know of an incredible green software repository that we missed? Let us know! This list is meant to continually grow and develop, so we welcome any suggestions from our community on how we can improve it. Create a [pull request](#contributing-to-githubs-green-software-directory) with a brief explanation to add a new project.

## Measurement
> Help measure and interpret the impact of emissions and the environmental impact of software use.
- [Scaphandre](https://github.com/hubblo-org/scaphandre): Scaphandre [skafɑ̃dʁ] is a metrology agent dedicated to electric power and energy consumption metrics. Use it to measure the power consumption of your tech services and get this data in a convenient form, sending it through any monitoring or data analysis toolchain.
- [Kepler](https://github.com/sustainable-computing-io/kepler): Kepler (Kubernetes-based Efficient Power Level Exporter) uses eBPF to probe performance counters and other system stats, uses ML models to estimate workload energy consumption based on these stats, and then exports them as Prometheus metrics. Use it to learn about energy consumption of Kubernetes components such as Pods and Nodes.
- [Codecarbon](https://github.com/mlco2/codecarbon): A Python package that estimates your hardware electricity power consumption (GPU + CPU + RAM) and then applies to it the carbon intensity of the region where the computing is done.
- [Cloud-carbon-footprint](https://github.com/cloud-carbon-footprint/cloud-carbon-footprint): A tool to estimate energy use (kilowatt-hours) and carbon emissions (metric tons CO2e) from public cloud usage.
- [Carbon-aware-sdk](https://github.com/Green-Software-Foundation/carbon-aware-sdk): A toolset to help you measure the carbon emissions of your software, in turn helping you measure and reduce your software's carbon emissions, and choose when and where you run your software to make it greener. 
- [CO2.js](https://github.com/thegreenwebfoundation/co2.js/): An open-source JavaScript library that enables you to estimate the carbon emissions produced by transferring bytes of data on the internet, get different forms of grid intensity data such as annual average and marginal data by country, and make automated queries against Green Web Foundation’s Green Domain’s dataset.
- [Carbontracker](https://github.com/lfwa/carbontracker): Track and predict the energy consumption and carbon footprint of training deep learning models.
- [Experiment-impact-tracker](https://github.com/Breakend/experiment-impact-tracker): A simple drop-in method to track energy usage, carbon emissions, and compute utilization of your system.
- [Eco2AI](https://github.com/sb-ai-lab/Eco2AI): The Eco2AI is a Python library for CO2 emission tracking. It monitors energy consumption of CPU & GPU devices and estimates equivalent carbon emissions taking into account the regional emission coefficient. The Eco2AI is applicable to all Python scripts and all you need is to add the couple of strings to your code. All emissions data and information about your devices are recorded in a local file.
- [Greenframe-cli](https://github.com/marmelab/greenframe-cli): Estimate carbon footprint of a user scenario on a web application.
- [Impact](https://github.com/mlco2/impact/): ML has an impact on the climate, but not all models are born equal. Calculate machine learning emissions and add the results to your paper with this generated latex template.
- [Zeus](https://github.com/ml-energy/zeus): Zeus is a library for (1) measuring the energy consumption of Deep Learning workloads and (2) optimizing their energy consumption.
- [Powerapi](https://github.com/powerapi-ng/powerapi): PowerAPI is a middleware toolkit for building software-defined power meters. Software-defined power meters are configurable software libraries that can estimate the power consumption of software in real-time. PowerAPI supports the acquisition of raw metrics from a wide diversity of sensors (eg., physical meters, processor interfaces, hardware counters, OS counters) and the delivery of power consumptions via different channels (including file system, network, web, graphical). As a middleware toolkit, PowerAPI offers the capability of assembling power meters «à la carte» to accommodate user requirements.
- [Green-cost-explorer](https://github.com/thegreenwebfoundation/green-cost-explorer): See how much of your cloud bill is spent on fossil fuels, so you can do the right thing and switch. We're in a climate crisis, remember? This will show you your climate-related spend analysis for AWS.
- [Green Metrics Tool](https://github.com/green-coding-solutions/green-metrics-tool): Measures the energy and CO2 consumption of software through a software life cycle analysis (SLCA).
- [Carbonalyser](https://github.com/carbonalyser/Carbonalyser): The add-on "Carbonalyser" allows you to visualize the electricity consumption and greenhouse gases (GHG) emissions that your Internet browsing leads to.
- [GreenIT-Analysis](https://github.com/cnumr/GreenIT-Analysis): GreenIT-Analysis est une extension pour navigateur qui vous permet de quantifier les impacts environnementaux d'un parcours utilisateur complet, même derrière un firewall et / ou une authentification applicative. L'outil vérifie également l'utilisation de bonnes pratiques visant à diminuer ces impacts.
- [Tracarbon](https://github.com/fvaleye/tracarbon): Tracarbon tracks your device's energy consumption and calculates your carbon emissions using your location.
- [Carbonifer](https://github.com/carboniferio/carbonifer): Command Line Tool to control carbon emission of your cloud infrastructure. Reading Terraform files, carbonifer plan will estimate future Carbon Emissions of infrastructure and help make the right choices to reduce Carbon footprint.
- [PyJoules](https://github.com/powerapi-ng/pyJoules): A Python library to capture the energy consumption of code snippets.
- [Powerjoular](https://github.com/joular/powerjoular): PowerJoular is a command line software to monitor, in real time, the power consumption of software and hardware components.
- [Eco CI Energy Estimation](https://github.com/green-coding-solutions/eco-ci-energy-estimation): A project aimed at estimating energy consumption in continuous integration (CI) environments.
- [Perun](https://github.com/Helmholtz-AI-Energy/perun): Perun is a Python package that calculates the energy consumption of Python scripts by sampling usage statistics from your Intel, Nvidia or AMD hardware components. It can handle MPI applications, gather data from hundreds of nodes, and accumulate it efficiently. perun can be used as a command-line tool or as a function decorator in Python scripts.
- [Cloud-scanner](https://github.com/Boavizta/cloud-scanner): Get Boavizta impact data for your aws cloud account usage.
- [E-footprint](https://github.com/publicissapient-france/e-footprint): The current perimeter is the carbon footprint associated with the fabrication and usage of servers, storage, network (usage only) and end-user devices necessary for the existence of a digital service. Other environmental impacts (water, rare earth metals, etc.) will be added soon through an integration with the Boavizta API, and the lifecycle phases of device transportation and end of life are currently considered negligible.
- [Carbon-tools](https://github.com/dvelasquez/carbon-tools): A set of CO2 footprint tools to measure the impact of the code we ship.
- [Ecoinfra](https://github.com/eco-infra/ecoinfra): Ecoinfra is a powerful tool that helps you predict, asses, and reduce the environmental impact of your cloud infrastructure. By integrating your existing or new IaC project you can harness predictive sustainability into your cloud operations.
- [PSElectricityMaps](https://github.com/cloudyspells/PSElectricityMaps): This PowerShell module is intended for retrieving emissions data from CO2 Signal for a supplied Azure Region during resource deployments. This is a lightweight solution making use of non-commercial functionality available with a free account at ElectricityMaps. This means the module is only able to get near-realtime emissions data and no prodictive values. This means this module is not a real solution for reduced carbon deployments and -software. It does however provide some nice realtime values so you can simulate the beheaviour of deployments and software based on emissions data without the cost of a paid account for such data. For example in lab- or proof of concept environments.
- [PSWattTime](https://github.com/cloudyspells/PSWattTime): This PowerShell module is intended for retrieving emissions data from WattTime for a supplied Azure Region during resource deployments. 
- [Carbon-appinsights](https://github.com/cloudyspells/carbon-appinsights): Azure Function for logging PSElectricityMaps results for Azure regions to Application Insights.
- [Energy-consumption-measuring-toolkit](https://github.com/Accenture/energy-consumption-measuring-toolkit): While running applications on-premises or in the cloud, the main consumers of power on a server will be the CPU, the GPU, the memory, and the Tech Stack. Estimating how much each consumes will give an estimate of how much power your server, or your application on a server, consumes.
- [Green Kernel](https://github.com/green-kernel): This project creates an addition to the Linux Kernel which enables developers and end-users to see and quantify the energy cost of their running software on a process level.
- [FrameworkBenchmarks](https://github.com/TechEmpower/FrameworkBenchmarks): This project provides representative performance measures across a wide field of web application frameworks. With much help from the community, coverage is quite broad and we are happy to broaden it further with contributions.
- [Energy-Languages](https://github.com/greensoftwarelab/Energy-Languages): The complete set of tools for energy consumption analysis of programming languages, using Computer Language Benchmark Game.
- [Coppers](https://github.com/ThijsRay/coppers): Measure energy consumption of unit tests, Rust.
- [Cloud-jewels](https://github.com/etsy/cloud-jewels): Estimate energy consumption using GCP Billing Data.
- [Green-algorithms-tool](https://github.com/GreenAlgorithms/green-algorithms-tool): The Green Algorithms project aims at promoting more environmentally sustainable computational science. It regroups calculators that researchers can use to estimate the carbon footprint of their projects, tips on how to be more environmentally friendly, training material, past talks etc.
- [Carbonara](https://github.com/digital4better/carbonara/): This is a custom element to compute web navigation carbon footprint.
- [Cpu-energy-meter](https://github.com/sosy-lab/cpu-energy-meter): A tool for measuring energy consumption of Intel CPUs.
- [IF](https://github.com/Green-Software-Foundation/if): Green Software Foundation's Impact Framework for environmental impacts of software.
- [Carmen](https://github.com/Green-Software-Foundation/if-carmen): Carmen (Carbon Measurement Engine) is an open-source tool by the Green Software Foundation that enables organizations to measure the carbon footprint of their cloud-based software at two critical levels: infrastructure and application. 
- [Experiment Runner](https://github.com/S2-group/experiment-runner): The Experiment Runner provides a framework for automatically executing measurement-based experiments on any platform with dedicated plugins for energy related metrics collection.
- [Android Runner](https://github.com/S2-group/android-runner): The Android Runner provides a framework for automatically executing measurement-based experiments on native and web applications running on Android devices with dedicated plugins for energy related metrics collection.
- [Robot Runner](https://github.com/S2-group/robot-runner): The Robot Runner provides a framework for automatically executing measurement-based experiments on robotics software with dedicated plugins for energy related metrics collection.
- [Cardamon](https://github.com/Root-Branch/cardamon-core): Cardamon is able to measure front-end websites and associated back-end server processes for end to end measurements compatible with ISO 21031 SCI specification.
- [EcoLogits](https://github.com/genai-impact/ecologits): Estimate and track energy consumption and environmental impacts of generative AI models via APIs.
- [BoaviztAPI](https://github.com/Boavizta/boaviztapi): Multi-criteria environmental impacts of IT resources taking into account hardware manufacturing and usage as a self-hostable API.
- [ecobenchmark-applicationweb-backend](https://github.com/Boavizta/ecobenchmark-applicationweb-backend): Benchmarking different webapp scenario to compare energy consumption on several programming languages and dev practices.
- [Aether](https://github.com/re-cinq/aether): Aether is a calculation engine that uses metrics of infrastructure and calculates emissions in real-time based on factors.
- [Cloud Assess](https://github.com/kleis-technology/cloud-assess): The next generation cloud carbon calculator: an open source tool to automatically assess your environmental footprint as a cloud service provider.
- [PowDroid](https://github.com/powdroid-project/powdroid): A lightweight tool for measuring the energy footprint of any Android application.
- [Power Hog](https://github.com/green-coding-solutions/hog/): A macOS tool that visualises the resource usage (energy, carbon, energy impact) of your processes over time.
- [PowerLetrics](https://github.com/green-kernel/powerletrics): PowerLetrics is an open-source framework designed to monitor and analyze power consumption metrics at the process level on Linux.
- [EcoSurf Analyser](https://github.com/les-enovateurs/estimate-good-website): A browser extension that provides sustainability scores for websites, helping users understand the environmental impact of their browsing habits.
- [AI Wattch](https://github.com/AIWattch/browser-extension): AI Wattch is a Chrome browser extension that estimates the carbon emissions of your ChatGPT conversations in real time.
- [EnergiBridge](https://github.com/tdurieux/EnergiBridge): A cross-platform tool designed to measure the energy consumption of software across various operating systems and hardware architectures. It simplifies the process of gathering energy data, aiding developers in creating more sustainable software solutions.
- [TCS Estimator](https://github.com/ScottLogic/sl-tech-carbon-estimator): Mapping an organization’s technology emissions using the Tech Carbon Standard structure.

## Carbon Efficiency
> Start making changes to your software and architecture to use less energy and emit less carbon.
- [Kube-green](https://github.com/kube-green/kube-green): A simple k8s add-on that automatically shuts down some of your resources when you don't need them.
- [Kernel_tuner](https://github.com/kerneltuner/kernel_tuner): Create optimized GPU applications in any mainstream GPU programming language (CUDA, HIP, OpenCL, OpenACC).
- [Ec0lint](https://github.com/ec0lint/ec0lint): Ec0lint is a static code analysis tool that provides users with hints on how to reduce the carbon footprint of their websites during the development process. Applying code changes suggested by ec0lint results in lower carbon emissions per visit, quicker loading and higher space efficiency. The tool is open-source and community-driven.
- [ecoCode](https://github.com/green-code-initiative/ecoCode): EcoCode is a collective project aiming to reduce environmental footprint of software at the code level. The goal of the project is to provide a list of static code analyzers to highlight code structures that may have a negative ecological impact: energy and resources over-consumption, "fatware", shortening terminals' lifespan, etc.
- [Geopm](https://github.com/geopm/geopm): The Global Extensible Open Power Manager (GEOPM) provides a framework to explore power and energy optimizations on platforms with heterogeneous mixes of computing hardware.
- [Ecocode-mobile](https://github.com/green-code-initiative/ecocode-mobile): Mobile apps running on top of battery-limited, android-powered devices are more than others concerned by the reduction of their environmental footprint. Hence, we created ecoCode android, the version of ecoCode project fully dedicated to the Android platform. It provides static code analyzers to highlight code structures that may have a negative ecological impact: energy over-consumption, "fatware", shortening devices' lifespan, etc.
- [EcoSonar](https://github.com/Accenture/EcoSonar): Raising the awareness of delivery teams to environmental issues: enabling development teams to consider the environmental impact of digital technology during development and to promote knowledge of best eco-design and accessibility practices.
- [EcoCode-ios](https://github.com/green-code-initiative/ecoCode-ios): Mobile apps running on top of battery-limited devices are more than others concerned by the reduction of their environmental footprint. Hence, we created ecoCode iOS, the version of ecoCode project fully dedicated to the iOS platform. It provides static code analyzers to highlight code structures that may have a negative ecological impact: energy over-consumption, "fatware", shortening devices' lifespan, etc.
- [pruna](https://github.com/PrunaAI/pruna): An AI inference optimization framework. This projects integrates major model compression algorithms in an unified way, to enable developers use faster, smaller, more efficient and greener models with a minimal overhead.
- [Tech Carbon Standard](https://github.com/ScottLogic/Technology-Carbon-Standard): Proposed Technology Carbon Standard that aims to provide a unified structure for understanding, quantifying, and reducing carbon emissions from an organisation's technology landscape.

## Carbon Awareness
> Learn behavior changes that will enable less carbon emissions.
- [Region-carbon-info](https://github.com/GoogleCloudPlatform/region-carbon-info): This repository contains sustainability characteristics of Google Cloud regions in a machine readable format. Read more on the Google Cloud website.
- [Carbon-aware-keda-operator](https://github.com/Azure/carbon-aware-keda-operator): This repo provides a Kubernetes operator that aims to reduce carbon emissions by helping KEDA scale Kubernetes workloads based on carbon intensity. 
- [Grid-intensity-go](https://github.com/thegreenwebfoundation/grid-intensity-go): A tool written in Go, designed to be integrated into Kubernetes, Nomad, and other schedulers, to help you factor carbon intensity into decisions about where and when to run jobs.
- [Vessim](https://github.com/dos-group/vessim): Vessim is a versatile co-simulation testbed for carbon-aware applications and systems which connects domain-specific simulators for renewable power generation and energy storage with real software and hardware.
- [Carbon-Aware-Computing](https://github.com/bluehands/Carbon-Aware-Computing): The goal of this project is to provide developers with hassle free, easy to use, ready to run tools for carbon aware computing. All libraries and data are open source and open data with unrestricted usage. Within private, open source and commercial software. This project will deliver a set of libraries, services and data. There are mostly extensions to other projects and all credits belong to them. To forecast the best execution time the Carbon Aware SDK from the Green Software Foundation is used. The Forecast and actual data is from Energy-Charts provided by Fraunhofer ISE. For UK the data is provided by UK National Grid ESO.
- [Carbon-minimiser](https://github.com/bbc/carbon-minimiser): The National Grid have created a Carbon Intensity API for Great Britain. This allows you to access to predictions for carbon intensity across England, Scotland, and Wales. The Carbon Minimiser sits on top of this, and allows you to estimate the optimal time to perform actions to reduce their impact on the planet, by choosing times when your area has a lower carbon intensity.
- [Hangfire.Community.CarbonAwareExecution](https://github.com/bluehands/Hangfire.Community.CarbonAwareExecution): A Hangfire extension to schedule tasks with carbon awareness in mind. The best point in time is calculated based on emission forecasts to get a window with a minimal grid carbon intensity.
- [Compute Gardener Scheduler](https://github.com/elevated-systems/compute-gardener-scheduler): Compute Gardener is an open source Kubernetes scheduler with the goal of making it much easier for a k8s cluster operator to immediately begin employing carbon or price signal aware strategies in order to shift deferrable jobs in time and space when power is cheaper or cleaner. Compute Gardener also captures all metrics necessary to validate mitigated emissions for reporting and future carbon credit generation purposes.

## Special Tools
- [Patterns](https://github.com/Green-Software-Foundation/patterns): An online open-source database of software patterns reviewed and curated by the Green Software Foundation across a wide range of categories.
- [Sustainable-software-guidelines](https://github.com/sustainable-software-guidelines/Sustainable-Software-Development): Guidelines for developing energy-efficient and sustainable software, by the Green Computing Pillar of the Green Digital Action Initiative. 
- [Nvidia-co2](https://github.com/kylemcdonald/nvidia-co2): Show gCO2eq emissions information with nvidia-smi, at the top right corner. For example: 79.2gCO2eq/h or 23.76mm^2/h sea ice.
- [Sustainability-scanner](https://github.com/awslabs/sustainability-scanner): Sustainability scanner is an open source tool that helps you create a more sustainable infrastructure on AWS. It takes in your Cloudformation template as input, evaluates it against a set of sustainability best practices and generates a report with a sustainability score and suggested improvements to apply to your template. 
- [Leaf](https://github.com/dos-group/leaf): LEAF is a simulator for analytical modeling of energy consumption in cloud, fog, or edge computing environments. It enables the modeling of simple tasks running on a single node as well as complex application graphs in distributed, heterogeneous, and resource-constrained infrastructures. LEAF is based on SimPy for discrete-event simulation and NetworkX for modeling infrastructure or application graphs.
- [Lite-youtube-embed](https://github.com/paulirish/lite-youtube-embed): Provide videos with a supercharged focus on visual performance. This custom element renders just like the real thing but approximately 224× faster.
- [Ipmitool](https://github.com/ipmitool/ipmitool): An open-source tool for controlling IPMI-enabled systems that gets the power consumption of a bare metal machine.
- [Ethereum-nft-activity](https://github.com/kylemcdonald/ethereum-nft-activity): How much energy does it take to power popular Ethereum-backed CryptoArt platforms? And what emissions are associated with this energy use?
- [Carbon.txt](https://github.com/thegreenwebfoundation/carbon.txt): A proposed convention for making it possible demonstrate that your infrastucture uses green power.
- [CarbonRunner](https://carbonrunner.io/): CarbonRunner automatically shifts compute, whether AI training or GitHub Actions, to the lowest-carbon regions across AWS, Azure, GCP and Heata in real time, cutting emissions by up to 90% compared to default GitHub Actions. With built-in ESG reporting, companies gain clear visibility into their cloud emissions and costs, while workloads are scheduled with water scarcity in mind and never run on servers above 100gCO₂/kWh. CarbonRunner brings measurement, carbon efficiency and carbon-aware orchestration together in one platform, making it easy to track existing workflows on GitHub, GitLab or Bitbucket and run them more sustainably.
  
---
### Contributing to GitHub's Green Software Directory
We are looking for projects **on GitHub** that are actively being used/developed and can be used by others.

- Create a fork of this project.
- Create a new branch.
- Add your project to a relevant category in the following format: [Project Name](Project URL) - A sentence that describes your project.
- Create a pull request and wait for it to be reviewed and merged.
- Further details on how create pull requests can be found in the official [GitHub documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
