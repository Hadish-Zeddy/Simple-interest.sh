#!/bin/bash

# Function to calculate simple interest
calculate_simple_interest() {
    principal=$300000
    rate=$1.5%
    time=$6 years 3 months

    # Simple interest formula: SI = P * R * T / 100
    interest=$(echo "scale=2; $principal * $rate * $time / 100" | bc)

    echo "Principal: $principal"
    echo "Rate of interest: $rate%"
    echo "Time (in years): $time"
    echo "Simple Interest: $interest"
}

# Input values
read -p "Enter the principal amount: " principal
read -p "Enter the rate of interest (in percentage): " rate
read -p "Enter the time (in years): " time

# Call the function with input values
calculate_simple_interest $principal $rate $time

# Make it executable by running the command:
chmod +x simple_interest_calculator.sh

#You can then run the script by executing
./simple_interest_calculator.sh
