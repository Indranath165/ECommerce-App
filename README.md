<h1>E-Commerce Website</h1>
This is an eCommerce website that showcases a wide array of expertly designed goods for the workspace, home, and travel. Built using Next.js, React, Sanity, Stripe, and TailwindCSS, it delivers a seamless and engaging shopping experience. Next.js and React power the dynamic user interface, while Sanity provides efficient content management. Stripe ensures secure payment processing, while TailwindCSS adds a sleek and modern design aesthetic. Explore this platform to discover unique products and elevate your surroundings with style and functionality.
<br> <br>
<b>A live demo of this website can be found at</b> <a href="https://e-commerce-app-steel.vercel.app/" target="_blank">https://e-commerce-app-steel.vercel.app/</a>.
<h2>Features</h2>
<ul>
    <li>User-friendly interface for browsing and searching products</li>
    <li>Product categories and filters for easy navigation</li>
    <li>Product details page with images, descriptions, and pricing</li>
    <li>Shopping cart functionality for adding and removing items</li>
    <li>Secure checkout process powered by Stripe integration</li>
    <li>Responsive design for seamless experience across devices</li>
</ul>
<h2>Installation</h2>
<ol>
    <li>Clone or download this repository to your local machine.</li>
    <li>Install dependencies: <code>npm install</code></li>
    <li>Configure environment variables-- Create a `.env` file in the root directory and add the following variables:
    <code>
    NEXT_PUBLIC_SANITY_PROJECT_ID= <br>
    NEXT_PUBLIC_SANITY_DATASET= <br>
    NEXT_PUBLIC_STRIPE_PUBLIC_KEY= <br>
    STRIPE_SECRET_KEY= </code></li>
    <li>To obtain the values for these variables, follow these steps:
    <ul>
        <li>`NEXT_PUBLIC_SANITY_PROJECT_ID` and `NEXT_PUBLIC_SANITY_DATASET`:</li>
        <ul>
            <li>Sign up or log in to your account on <a href="https://www.sanity.io/" target="_blank">Sanity.io</a></li>
            <li>Create a new project and set up a new dataset for your eCommerce website.</li>
            <li>Retrieve the project ID and dataset name from your Sanity project settings and assign them to the respective variables in the `.env` file.</li>
        </ul>
        <li>`NEXT_PUBLIC_STRIPE_PUBLIC_KEY` and `STRIPE_SECRET_KEY`:</li>
        <ul>
            <li>Sign up or log in to your account on <a href="https://stripe.com/" target="_blank">Stripe</a></li>
            <li>Create a new project and set up the necessary configurations.</li>
            <li>Retrieve the public key and secret key from your Stripe project settings and assign them to the respective variables in the `.env` file.</li>
        </ul>
        <li>Make sure to replace the empty values with the actual keys in the `.env` file.</li>
    </ul></li>
    <li>Run the development server: <code>npm run dev</code></li>
    <li>The website will be running locally at <a href="http://localhost:3000" target="_blank">http://localhost:3000</a>.</li>
</ol>
<h2>Technologies Used</h2>
<ul>
    <li><b>Next.js</b>: A React framework for building server-rendered and statically generated web applications.</li>
    <li><b>React</b>: A JavaScript library for building user interfaces.</li>
    <li><b>Sanity</b>: A headless CMS (Content Management System) for structuring and managing content in a customizable way.</li>
    <li><b>Stripe</b>: A payment processing platform for accepting online payments securely.</li>
    <li><b>Tailwind CSS</b>: A highly customizable CSS framework that provides a utility-first approach for building modern and responsive user interfaces.</li>
</ul>
<h2>Contributions</h2>
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
<ul>
    <li>Fork the repository.</li>
    <li>Create a new branch.</li>
    <li>Make your changes and commit them.</li>
    <li>Push your changes to your forked repository.</li>
    <li>Submit a pull request describing the changes you've made.</li>
</ul>
