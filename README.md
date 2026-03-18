# HelloApp

Hello App starts with Hello World, progresses to displaying a user name, then names from command-line args and standard input. It then manages names in a collection with list/remove options, refactors into methods and classes, adds persistence across runs, and finally displays names in banner format.

## Purpose

HelloApp is a step-by-step Java learning project that demonstrates progression from core syntax and I/O to collection handling, clean architecture, and persistence.

## Use Cases

| UC  | Description                                      |
|-----|--------------------------------------------------|
| UC1 | Print a basic greeting in the console            |
| UC2 | Accept one name via command-line input           |
| UC3 | Support optional argument handling               |
| UC4 | Handle multiple command-line names               |
| UC5 | Read a single name from standard input           |
| UC6 | Read and process multiple names from stdin       |
| UC7 | Store entered names in memory and list them      |
| UC8 | Add removal support for stored names             |
| UC9 | Extract input-processing logic into methods      |
| UC10| Move name-management into a separate class       |
| UC11| Persist names to storage across runs             |
| UC12| Render greeting text in banner-style output      |

## Project Structure

```
HelloApp/
├── src/
│   └── main/
│       └── java/
│           └── HelloApp.java
├── docs/
│   └── HelloAppUC.md
├── pom.xml
├── .gitignore
└── README.md
```

## How to Run

### Prerequisites
- Java 11+
- Maven 3.6+

### Build
```bash
mvn clean install
```

### Run
```bash
mvn exec:java -Dexec.mainClass="HelloApp"
```
