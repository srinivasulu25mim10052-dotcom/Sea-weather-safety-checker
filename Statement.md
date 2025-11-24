Problem Statement:

Small boat owners, fishermen, and tourists often venture into the sea without accurately assessing the combined risks of wind, waves, and rain. This lack of awareness can lead to dangerous situations, capsizing, or accidents. There is a need for a simple, immediate tool that interprets raw weather numbers into clear "Go/No-Go" safety advice.

Scope of the Project:

Current Scope (MVP - Minimum Viable Product):


The project is a text-based application (CLI) that requires manual data entry.

It analyzes three specific parameters: Wave Height, Wind Speed, and Rain Condition.

It provides three specific output states: Safe, Caution, and Dangerous.


Future Scope (Optional ideas for expansion):


Fetching live weather data automatically from an API (so users don't have to type it).

Adding specific alerts for different types of boats (e.g., "Safe for large ships, Unsafe for kayaks").


Target Users:

Local Fishermen: Who need a quick check before launching small boats.

Tourists/Beachgoers: Deciding if it is safe to swim or rent a jet ski.

Lifeguards: To quickly standardize the flag color (Green/Yellow/Red) for the day.

Sailing Hobbyists: Beginners who are learning safe weather thresholds.


High-Level Features:


These features map directly to your code logic:



Safety Logic Engine: The core if/elif/else block that determines risk levels based on pre-set safety thresholds .

Multi-Factor Assessment: The ability to evaluate multiple danger factors (Wind + Wave + Rain) simultaneously rather than looking at just one.

User Alert System: Clear, text-based feedback using visual indicators  to ensure the safety message is understood instantly.

Input Validation: The ability to accept floating-point numbers for precise measurements .
