# Movie Recommender
A simple yet effective machine learning-based movie recommender system. Given the name of a movie you like, the engine suggests similar movies based on content similarity.

## 🚀 Features

- Input a movie title and receive a list of similar movies.
- Uses natural language processing techniques to compare movie descriptions.
- Command-line interface built for easy use via the PyCharm terminal.
- Lightweight and easy to customize or expand with more data.

## 🛠️ Tech Stack

- **Language**: Python
- **Tools**: PyCharm
- **Libraries**:
  - `pandas`
  - `scikit-learn`
  - `numpy`
 
## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fizakabeer/MovieRecommender.git
   cd MovieRecommender
2. **Instal required packages**:
   ```bash
   pip install -r requirements.txt
3. **Run the engine**:
   ```bash
   python movie_recommender_engine.py

## 🧠 How It Works

The engine uses **TF-IDF vectorization** to transform movie descriptions into numerical vectors that capture the importance of each word. It then calculates **cosine similarity** between these vectors to find movies with similar plot descriptions. This allows the recommender to suggest movies closely related in content to the one you input.

## 📈 Example
```bash
Enter the name of the movie you like: Avatar
Movies you might like: 
Guardians of the Galaxy
Aliens
Star Wars: Clone Wars: Volume 1
Star Trek Into Darkness
Star Trek Beyond
Alien
Lockout
Jason X
The Helix... Loaded
Moonraker
Planet of the Apes
Galaxy Quest
Gravity
Alien³
Jupiter Ascending
The Wolverine
Silent Running
Zathura: A Space Adventure
Trekkies
Cargo
Wing Commander
Star Trek
Lost in Space
Babylon A.D.
The Fifth Element
Oblivion
Titan A.E.
AVP: Alien vs. Predator
The Empire Strikes Back
Dragonball Evolution
Superman Returns
Divergent
John Carter
The Black Hole
The Ice Pirates
Memoirs of an Invisible Man
Starship Troopers
The Astronaut's Wife
Machete Kills
Soldier
The Abyss
Damnation Alley
Men in Black
Space Cowboys
Space Dogs
The Time Machine
Sheena
Captain America: Civil War
Star Trek: Insurrection
Oz: The Great and Powerful
```

## 📌 Future Improvements

- Add genre and rating filters to refine recommendations.
- Build a graphical user interface (GUI) or web app for easier interaction.
- Expand the dataset to include user ratings for collaborative filtering.
- Improve natural language processing with advanced models like BERT.

## 👤 Author

- [Fiza Kabeer](https://github.com/fizakabeer)

## 📄 License

This project is licensed under the MIT License.
