# Zork Undertale

Java text adventure final project for AP CS, inspired by Zork and Undertale.

## Requirements

- JDK 11+

## Run

From the repository root on Windows:

```powershell
cd TextAdventure
javac -cp "lib/*" -d out src/zork/*.java
java -cp "out;lib/*" zork.Zork
```

On macOS or Linux, use `out:lib/*` as the Java classpath instead of `out;lib/*`.

## Project Layout

- `TextAdventure/src/zork/` contains the game source.
- `TextAdventure/src/zork/data/` contains room data, ASCII art, and music assets.
- `TextAdventure/lib/` contains bundled runtime libraries.
