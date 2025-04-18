## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/wilson7777777/simple-video-streaming-platfrom.git](https://github.com/wilson7777777/simple-video-streaming-platfrom.git)
    cd simple-video-streaming-platfrom
    ```

2.  **Place your video files:**
    Put your video files (e.g., `my_video.mp4`) into the `web/videos/` directory. For this simple demonstration, using smaller video files is recommended. Avoid committing large video files directly to the repository.

3.  **Run the service using Docker Compose:**
    ```bash
    docker compose up -d --build
    ```

4.  **Access the service:**
    Open your web browser and navigate to `http://localhost:8080/`.
