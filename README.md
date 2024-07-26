# Project: Simple Conversational Assistant using Rasa

## Introduction

In this project, I create a simple conversational assistant using Rasa, an open-source framework for building AI assistants and chatbots.

## Project Structure

- `data/`
  - Training data for NLU and dialogue management.
- `models/`
  - Stores trained models.
- `actions/`
  - Custom action definitions.
- `domain.yml`
  - Defines intents, entities, slots, responses, and actions.
- `config.yml`
  - Configuration for the training pipeline and policies.
- `endpoints.yml`
  - Configuration for bot endpoints.

## Getting Started

### Prerequisites

Ensure I have the following installed:

- Python 3.7+
- Rasa Open Source
- A text editor or IDE

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Training the Model

To train the NLU and dialogue management models, run:
```bash
rasa train
```

### Running the Assistant

To start the Rasa server:
```bash
rasa shell
```

### Custom Actions

If there are custom actions, start the action server:
```bash
rasa run actions
```

### Testing

Test the assistant in interactive mode:
```bash
rasa interactive
```
