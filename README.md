# Voting System

This is a simple console-based voting system implemented in Python. It allows users to register as voters, cast votes for candidates, and view the voting results.

## Features

- **Signup**: Users can register as voters by providing their name, age, and a legal ID proof.
- **Vote**: Registered voters can cast their vote for one of the available candidates.
- **Display Results**: View the current voting results showing the number of votes each candidate has received.

## Requirements

- Python 3.x
- `voters.json` file (will be created automatically if it doesn't exist)

## Setup

1. Clone the repository or download the source code.
2. Ensure you have Python 3.x installed on your system.
3. Run the `voting.py` script using the command:
   ```bash
   python voting.py
   ```

## Usage

1. **Signup**: Choose option 1 to register as a voter. You must be at least 18 years old and provide a valid ID proof.
2. **Vote**: Choose option 2 to cast your vote. You need to enter your Voter ID to proceed.
3. **Display Results**: Choose option 3 to view the current voting results.
4. **Exit**: Choose option 4 to exit the application.

## Legal ID Proofs

The following ID proofs are accepted for voter registration:
- Aadhar
- Passport
- Driving License
- Voter ID

## Note

- Each voter can only vote once.
- Ensure the `voters.json` file is in the same directory as the `voting.py` script.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Contact

For any questions or feedback, please contact [Your Name] at [Your Email].
