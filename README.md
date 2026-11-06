# Periodic Table Database

A PostgreSQL database containing information about chemical elements.

## Project Files

- `periodic_table.sql` - Database dump.
- `element.sh` - Bash script for searching elements.

## How to Use

Run the script with an element's atomic number, symbol, or name.

Examples:

```bash
./element.sh 1
./element.sh H
./element.sh Hydrogen

## Database Tables

- `elements` - Stores the atomic number, symbol, and name.
- `properties` - Stores atomic mass, melting point, boiling point, and type ID.
- `types` - Stores the element classifications: metal, nonmetal, and metalloid.
