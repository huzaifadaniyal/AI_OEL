# Genetic Algorithm for Binary Schedule Optimization

This project implements a simple Genetic Algorithm (GA) to optimize a binary schedule. The algorithm evolves a population of binary strings to maximize the sum of the bits in the schedule.

## Features
- **Fitness Function**: The fitness is calculated as the sum of the bits in a binary string.
- **Selection**: Roulette Wheel Selection is used to select parents based on their fitness.
- **Crossover**: Single-point crossover is applied to create offspring.
- **Mutation**: Random bit flips are performed to introduce variability.

## How to Run
1. Install Python (version 3.x).
2. Save the script as `genetic_algorithm.py`.
3. Run the script in a terminal or an IDE:
   ```bash
   python genetic_algorithm.py
   ```

## Example Output
```text
Generation 1:
Population: [...]
Fitnesses: [...]
Best in Generation: Schedule 110011101110111000011111 with Fitness: 16

...

Final Best Solution: Schedule 101011101111111111111110, Fitness: 20
```

## Customization
- **Population Size**: Adjust `pop_size` for larger or smaller populations.
- **Gene Length**: Modify `gene_length` to increase or decrease schedule length.
- **Generations**: Change the number of `generations` to run the algorithm longer.
- **Crossover and Mutation Rates**: Tune `crossover_rate` and `mutation_rate` for experimentation.

## Files
- `genetic_algorithm.py`: The Python script implementing the Genetic Algorithm.

## License
This project is licensed under the MIT License.

---

Developed for learning and demonstration purposes.
