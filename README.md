<h1 align="center">
  <br>
  Conway's Game of Life
  <br>
</h1>

<h3 align="left">Rules</h3>

- Any live cell with fewer than two live neighbours dies, as if by underpopulation.
- Any live cell with two or three live neighbours lives on to the next generation.
- Any live cell with more than three live neighbours dies, as if by overpopulation.
- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

## Draw then press space to play/pause

![game of life gif](https://github.com/brunonobrega/game-of-life/assets/15756782/3113b24a-ad7b-48a6-b040-e1ce378131c1)

## How To Run

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python 3](https://www.python.org/downloads) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/brunonobrega/game-of-life.git

# Go into the repository
$ cd game-of-life

# Install dependencies
$ pip install -r requirements.txt

# Run the app
$ python main.py
```

## Credits

This software uses the following open source packages:

- [Pygame](https://www.pygame.org/)
- [NumPy](https://numpy.org/)
