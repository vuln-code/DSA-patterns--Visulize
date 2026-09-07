# DSA-patterns--Visulize
This repo contains the code file of dsa visuliser simulator which is only for the revision of the dsa patterns and quick go through it.


🚀 DSA Patterns Master Cheatsheet & Visualizer

An interactive, single-page web application designed for fast competitive programming revision and technical interview prep. This tool breaks down four core array algorithm patterns into intuitive mind maps, detailed question taxonomies, edge-case tweaks, production-ready C++ templates, and live visual step simulations.

🌟 Features

🎯 Decision Engine (Pattern Identifier): Input your problem's constraints (e.g., sorted array, negative numbers allowed, static queries) to immediately get the best pattern recommendation and necessary code tweaks.

🧠 1-Liner Mind Maps: Clear, quick-reference concepts for instant memory recall during revision.

⚡ Master Tweaks & Edge-Case Matrix: Detailed breakdown showing exactly where standard logic breaks (e.g., negative numbers in sliding windows, circular arrays in Kadane's) and how to fix it in code.

💻 Ready-to-Copy C++ Templates: Production-ready C++ code snippets with tabbed navigation for alternate edge cases (e.g., duplicate skipping, 2D range sum).

🎨 Live Interactive Visualizer: An HTML5 Canvas simulator that steps through pointer movements, sliding window boundaries, and running variables in real-time.

📊 Complexity Benchmark: Built-in horizontal bar chart comparing time and space metrics across all patterns.

📚 Covered Patterns

Two Pointers: Opposite-end traversal, fast & slow pointers, skipping duplicates, target sum search.

Sliding Window: Fixed window size $K$, dynamic variable-length windows (min/max bounds), frequency matching.

Kadane's Algorithm: Standard maximum contiguous subarray sum, circular wrapping array tweak, max product subarray.

Prefix Sum: $1\text{D}$ range sum precomputation ($O(1)$ queries), "Subarray Sum = K" with Hash Maps, negative modulo arithmetic.

🛠️ How to Run Locally

Because this application is built as a single-page HTML application with zero external build dependencies, running it locally is as simple as opening a file:

Download or clone this repository to your computer.

Double-click index.html (or right-click and choose Open with Browser).

That's it! No npm install, Node.js server, or build steps required.

🌐 Free Deployment Options

You can deploy this site live in less than 2 minutes using any of the following free hosting platforms:

Option A: GitHub Pages (Recommended)

Push your repository containing index.html to GitHub.

Go to Settings > Pages in your repository.

Under Branch, select main (or master) and set the folder to / (root).

Click Save. Your site will be live at https://yourusername.github.io/repository-name/.

Option B: Netlify Drop

Go to Netlify Drop.

Drag and drop the folder containing your index.html file into the upload box.

Netlify will generate a live URL instantly!

Option C: Vercel

Install Vercel CLI (npm i -g vercel) or sign in at Vercel.com.

Import your GitHub repository or run vercel in your project folder.

Click Deploy.

🗺️ Roadmap & Future Upgrades

Planned enhancements for future versions:

[ ] New Patterns: Fast & Slow Pointers (Floyd's Cycle), Merge Intervals, Monotonic Stack, Backtracking, and Binary Search variants.

[ ] Multi-Language Support: Toggle code templates between C++, Python, Java, and JavaScript.

[ ] Custom Array Input: Allow users to type their own array inputs into the visual step simulator.

📄 License

This project is open-source and free to use for personal learning, interview practice, and educational purposes.
