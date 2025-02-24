# Profile Page with Flask

This project demonstrates how to create a static profile page using HTML and CSS, and serve it using Python Flask.

## Features
1. **Frontend**:
   - A clean and responsive profile page with a heading, image, bio, and links.
   - Styled using CSS for a modern look.

2. **Backend**:
   - Flask serves the static profile page at the `/profile` route.
   - Redirects the default route (`/`) to `/profile`.
   - Uses `render_template` to serve the HTML file.
   - Serves static resources (CSS and images) from the `static` folder.

## How to Run
1. Clone the repository.
2. Install Flask: `pip install flask`.
3. Run the Flask app: `python app.py`.
4. Open your browser and go to `http://127.0.0.1:5000/`.

## Advanced Features
- The profile page is rendered using `render_template`.
- The default route (`/`) redirects to `/profile`.