# Periodic Table Database

This project contains a PostgreSQL database of chemical elements and a bash script to query element information.

## Files
- `element.sh` - Bash script to query element information
- `periodic_table.sql` - Database dump file

## Usage
Run the script with an atomic number, symbol, or element name:
```bash
./element.sh 1
./element.sh H
./element.sh Hydrogen
```

## Database Structure
The database contains three tables:
- `elements` - atomic number, symbol, and name
- `properties` - atomic mass, melting point, boiling point, and type
- `types` - element types (metal, nonmetal, metalloid)
