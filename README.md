# How to Compile and Start the Project

Use the Terminal. The following example commands are for **Ubuntu Linux** via **Windows Subsystem for Linux (WSL)**.

## Step 1: Create the Database

Create a `coffee.db` file and execute the statements in `init.sql` using **DuckDB**:

```bash
duckdb coffee.db < init.sql
```

## Step 2: Compile the project via Maven
```bash
mvn compile
```

## Step 3: Start the project via Maven
```bash
mvn exec:java
```

## Notes:
If Java is not installed, install Java:

```bash
sudo apt install default-jdk -y
```

If Maven is not installed, install Maven:
```bash
sudo apt install maven
```
