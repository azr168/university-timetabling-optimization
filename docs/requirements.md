# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow administrators to manage academic data, including courses, lecturers, room capacities, and available time slots. (FR1)
2. The system shall allow users to define and configure hard constraints (e.g., no room or lecturer double-booking) and soft constraints (e.g., minimizing student class gaps). (FR2)
3. The system shall execute a Genetic Algorithm to automatically construct an optimized academic timetable based on the configured constraints. (FR3)
4. The system shall display the generated timetable in an interactive visual view, highlighting any remaining constraint penalties or conflict scores. (FR4)
5. The system shall allow users to export the finalized timetable into standard file formats (such as CSV or PDF) for distribution. (FR5)

## Non-functional requirements (how the system must PERFORM)
1. The system shall complete the Genetic Algorithm optimization process and output a schedule within 30 seconds for a dataset of up to 50 courses and 20 rooms. (NFR1)
2. The system shall achieve a 0% hard constraint violation rate in the final generated schedule across 100% of successful optimization runs. (NFR2)
3. The system shall load user interface views and respond to interactive navigation requests within 2 seconds. (NFR3)
