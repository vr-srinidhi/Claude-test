# Claude-test — Hello World Website

A simple Hello World static website built with HTML and CSS.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 |
| Server | nginx (via Docker) |

## How to Run

### With Docker (Recommended)

**Requirements:** Docker Desktop

1. Clone the repository:
   ```bash
   git clone https://github.com/vr-srinidhi/Claude-test.git
   cd Claude-test
   ```

2. Build the Docker image:
   ```bash
   docker build -t claude-test .
   ```

3. Run the container:
   ```bash
   docker run -d -p 8080:80 --name claude-test claude-test
   ```

4. Open your browser and go to:
   ```
   http://localhost:8080
   ```

### Without Docker

**Requirements:** Python 3 (pre-installed on most systems)

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Where to Launch

| Environment | URL |
|-------------|-----|
| Docker | http://localhost:8080 |
| Python server | http://localhost:8080 |

## Project Structure

```
Claude-test/
├── index.html    # Main page
├── style.css     # Styles
├── Dockerfile    # Docker configuration
└── README.md     # This file
```
