# Free Aviation Tools & Flight Planning Calculators

Free aviation tools and calculators for pilots, flight dispatchers, charter operators and flight operations teams.

This repository brings together practical aviation calculators for flight planning, crew duty, aircraft performance and day to day operations. The tools are free to use online and are maintained by [FlightStratix](https://flightstratix.com/).

Use the calculators directly online, read the calculation methodology, or explore the supporting aviation resources in this repository.

## Aviation Tools

| Tool                                 | What it does                                                             | Use Online                                                                                  |
| ------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------- |
| Airport Lookup                       | Find airport ICAO and IATA codes, runway information and airport details | [Open Airport Lookup](https://flightstratix.com/airport-lookup)                             |
| Flight Time Calculator               | Calculate estimated flight time between airports                         | [Open Flight Time Calculator](https://flightstratix.com/flight-time-calculator)             |
| Aviation Fuel Calculator             | Calculate aviation fuel requirements and convert fuel quantities         | [Open Fuel Calculator](https://flightstratix.com/fuel-calculator)                           |
| Aircraft Weight & Balance Calculator | Calculate aircraft weight, balance and loading information               | [Open Weight & Balance Calculator](https://flightstratix.com/weight-and-balance-calculator) |
| EASA FTL Calculator                  | Check flight duty periods and crew duty limits                           | [Open FTL Calculator](https://flightstratix.com/ftl-calculator)                             |
| Crosswind Calculator                 | Calculate crosswind and headwind components                              | [Open Crosswind Calculator](https://flightstratix.com/crosswind-calculator)                 |

More aviation calculators and operational tools will be added as they are released.

---

## Who These Aviation Tools Are For

The tools are intended for people working across private, business and commercial aviation, including:

* Pilots
* Flight dispatchers
* Flight operations officers
* Charter operators
* Trip support teams
* Corporate flight departments
* Aviation students
* Ground operations teams
* Crew scheduling teams
* Aviation professionals

They are intended to make common aviation calculations and lookups easier to access without requiring a full flight operations system.

---

# Flight Planning Tools

## Flight Time Calculator

The Flight Time Calculator estimates flight duration between two airports using route distance and aircraft speed information.

It can be useful when:

* estimating sector times
* preparing charter quotations
* checking initial flight feasibility
* comparing aircraft
* planning multi sector trips
* estimating block time

### Typical calculation

A simplified flight time calculation starts with:

```text
Flight Time = Distance ÷ Ground Speed
```

Operational flight time may then include factors such as:

* wind
* routing
* departure procedures
* arrival procedures
* aircraft performance
* taxi time
* ATC restrictions

Use the online calculator:

[Flight Time Calculator](https://flightstratix.com/flight-time-calculator)

---

## Airport Lookup

Search aviation airport information using ICAO or IATA codes.

Airport information can be useful when preparing:

* flight plans
* charter quotations
* handling requests
* fuel requests
* passenger itineraries
* operational flight briefs
* airport suitability checks

Depending on available data, airport records may include information such as:

* ICAO code
* IATA code
* airport name
* coordinates
* runway information
* location
* elevation
* timezone

Use the tool:

[Airport Lookup](https://flightstratix.com/airport-lookup)

---

## Crosswind Calculator

Crosswind is the component of wind acting perpendicular to the runway.

A crosswind calculation commonly uses:

```text
Crosswind Component = Wind Speed × sin(Wind Angle)
```

The headwind or tailwind component can be calculated using:

```text
Headwind Component = Wind Speed × cos(Wind Angle)
```

This can help pilots and operations teams compare reported wind conditions against aircraft or operator limitations.

Use the tool:

[Crosswind Calculator](https://flightstratix.com/crosswind-calculator)

---

# Aircraft Calculators

## Aircraft Weight & Balance Calculator

Aircraft weight and balance calculations help determine whether an aircraft remains within approved loading limits.

A typical calculation considers:

* aircraft basic empty weight
* crew
* passengers
* baggage
* cargo
* fuel
* individual station arms
* moments
* centre of gravity

The basic relationship is:

```text
Moment = Weight × Arm
```

Centre of gravity can then be calculated from:

```text
CG = Total Moment ÷ Total Weight
```

Actual loading limits depend on the aircraft type, approved aircraft documentation and operator procedures.

Use the tool:

[Aircraft Weight & Balance Calculator](https://flightstratix.com/weight-and-balance-calculator)

---

# Aviation Fuel Tools

## Aviation Fuel Calculator

The Aviation Fuel Calculator helps with common fuel calculations and fuel quantity conversions used during flight planning.

Typical aviation fuel planning may account for:

* taxi fuel
* trip fuel
* contingency fuel
* alternate fuel
* final reserve fuel
* additional fuel
* discretionary fuel

Exact fuel planning requirements depend on aircraft type, operator procedures, jurisdiction and applicable regulations.

The calculator should be used as a planning aid and should not replace an operator's approved fuel policy or aircraft documentation.

Use the tool:

[Aviation Fuel Calculator](https://flightstratix.com/fuel-calculator)

---

# Crew & Flight Duty Tools

## EASA FTL Calculator

Flight Time Limitation calculations help operators determine whether planned crew duties remain within applicable duty and rest requirements.

FTL calculations may depend on factors including:

* duty start time
* number of sectors
* acclimatisation
* reporting time
* planned FDP
* extensions
* split duty
* standby
* previous duties
* rest
* disruptive schedules

Because flight duty regulations contain conditions and exceptions, users should always check the current applicable regulations and their operator approved scheme.

Use the calculator:

[EASA FTL Calculator](https://flightstratix.com/ftl-calculator)

---

# Calculation Methodology

We want the calculations behind these tools to be understandable rather than hidden behind a result.

Documentation for individual tools can be stored inside the repository:

```text
docs/
├── flight-time-calculator.md
├── airport-lookup.md
├── aviation-fuel-calculator.md
├── weight-and-balance.md
├── easa-ftl-calculator.md
└── crosswind-calculator.md
```

Each methodology page should explain:

1. What the calculator does
2. Required inputs
3. Formula or calculation method
4. Assumptions
5. Worked examples
6. Limitations
7. Regulatory references where applicable
8. Date of the latest technical review

---

# Worked Examples

## Flight Time Example

Example:

```text
Distance: 600 NM
Average Ground Speed: 400 KT

Estimated Flight Time:
600 ÷ 400 = 1.5 hours

Estimated Flight Time:
1 hour 30 minutes
```

Real flight time can differ because of winds, ATC routing, climb, descent and airport procedures.

---

## Crosswind Example

Example:

```text
Runway Heading: 090°
Wind: 120° / 20 KT

Difference:
30°

Crosswind:
20 × sin(30°)

Crosswind:
10 KT
```

The example is for explanation only. Operational decisions should use current weather information, approved aircraft limitations and operator procedures.

---

## Weight & Balance Example

Example:

```text
Weight: 1,000 kg
Arm: 2.5 m

Moment:
1,000 × 2.5

Moment:
2,500 kg·m
```

Individual moments are combined to calculate the aircraft's total moment and centre of gravity.

---

# Regulatory & Technical Sources

Where a calculator relates to regulated flight operations, methodology should refer directly to current primary sources.

Useful authorities include:

## EASA

European Union Aviation Safety Agency

Relevant areas can include:

* Air Operations
* ORO.FTL
* Certification Specifications for Flight Time Limitations

Official website:

https://www.easa.europa.eu/

## FAA

Federal Aviation Administration

Relevant references may include:

* Federal Aviation Regulations
* Part 91
* Part 117
* Part 121
* Part 135
* Aeronautical Information Manual
* Advisory Circulars

Official website:

https://www.faa.gov/

## ICAO

International Civil Aviation Organization

ICAO publishes international Standards and Recommended Practices covering many areas of international aviation.

Official website:

https://www.icao.int/

Always confirm that the current version of the applicable regulation or publication is being used.

---

# Safety Notice

These aviation tools are provided for planning, educational and operational support purposes.

They do not replace:

* approved aircraft flight manuals
* operator manuals
* operational control procedures
* regulatory requirements
* approved FTL schemes
* official weather information
* NOTAMs
* flight planning systems
* pilot or dispatcher judgement

Users remain responsible for checking calculations against the documentation, regulations and procedures applicable to their operation.

If you identify a calculation issue, outdated regulation or incorrect assumption, please open a GitHub issue.

---

# Report an Issue

Aviation regulations, data and operational requirements change.

If you find:

* incorrect calculations
* outdated regulatory information
* incorrect airport information
* broken links
* unclear methodology
* calculation edge cases

please create an issue in this repository.

When reporting a calculation issue, include where possible:

```text
Tool:
Input:
Expected result:
Actual result:
Regulation or reference:
Additional notes:
```

This makes the issue easier to reproduce and review.

---

# Contributing

Contributions and technical feedback are welcome.

You can contribute by:

* reporting calculation problems
* suggesting aviation tools
* improving documentation
* providing test cases
* identifying outdated references
* suggesting formula corrections
* improving worked examples
* submitting code improvements

Before making a major change, please open an issue explaining what you would like to change.

---

# Planned Aviation Tools

Possible additions to the collection include:

## Flight Planning

* Great Circle Distance Calculator
* Climb Calculator
* Descent Calculator
* Top of Descent Calculator
* True Airspeed Calculator
* Ground Speed Calculator
* Wind Correction Calculator

## Weather

* METAR Decoder
* TAF Decoder
* Density Altitude Calculator
* Pressure Altitude Calculator
* Cloud Base Calculator

## Crew

* Crew Duty Calculator
* Rest Calculator
* FAA Part 117 Calculator
* Duty Period Calculator

## Aircraft

* Aircraft Registration Lookup
* Fuel Conversion Calculator
* Payload Calculator
* Takeoff Performance Reference Tools

## Dispatch & Operations

* NOTAM Decoder
* ICAO Flight Plan Tools
* Airport Code Converter
* UTC Time Converter
* Aviation Unit Converter

If there is an aviation calculator you would like to see added, open an issue.

---

# Repository Structure

The repository can be organised as follows:

```text
free-aviation-tools/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
│
├── calculators/
│   ├── crosswind/
│   ├── flight-time/
│   ├── fuel/
│   └── aviation-units/
│
├── docs/
│   ├── flight-time-calculator.md
│   ├── airport-lookup.md
│   ├── aviation-fuel-calculator.md
│   ├── weight-and-balance.md
│   ├── easa-ftl-calculator.md
│   └── crosswind-calculator.md
│
├── examples/
│   ├── flight-time-example.md
│   ├── crosswind-example.md
│   └── weight-and-balance-example.md
│
└── tests/
```

---

# Why This Repository Exists

Aviation operations teams still carry out a surprising number of everyday calculations using spreadsheets, manual formulas and disconnected websites.

We wanted to make commonly used aviation calculations easier to access and easier to understand.

Rather than hiding how a result is produced, the goal of this repository is to gradually document the formulas, assumptions, examples and references behind the tools.

The online calculators remain free to use.

---

# About FlightStratix

[FlightStratix](https://flightstratix.com/) is an aviation operations platform for charter operators, trip support companies, FBOs and flight departments.

FlightStratix connects operational and commercial information around the trip, including areas such as:

* trip management
* aircraft scheduling
* crew scheduling
* FTL checks
* quotations
* services
* passengers
* documents
* invoicing
* operational records

The software platform is separate from the free aviation tools in this repository.

Learn more:

[FlightStratix Aviation Operations Platform](https://flightstratix.com/)

---

# Maintained By

**FlightStratix**

Aviation operations software and free aviation tools for flight operations teams.

Website:
https://flightstratix.com/

GitHub issues should be used for calculator bugs, technical questions and contribution requests.

---

# License

Add the appropriate open source licence for any code published in this repository.

For example:

```text
MIT License
```

Individual aviation data sources may have their own licensing or usage conditions and should be documented separately where applicable.

---

⭐ If these free aviation tools are useful to you, consider starring the repository.

It helps other pilots, dispatchers and aviation professionals discover the project.
