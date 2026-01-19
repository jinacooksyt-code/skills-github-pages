<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chirag's Cafe - Home Delivery & Take Away</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #8B4513; /* Brown for cafe theme */
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #A0522D;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .menu-item {
            display: inline-block;
            width: 30%;
            margin: 10px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
            padding: 10px;
        }
        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }
        .order-form {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 20px auto;
        }
        input, select, button {
            display: block;
            width: 100%;
            margin: 10px 0;
            padding: 10px;
        }
        button {
            background-color: #8B4513;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #A0522D;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
        @media (max-width: 768px) {
            .menu-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Chirag's Cafe</h1>
        <p>Fresh, delicious food with home delivery and take away options!</p>
    </header>
    <nav>
        <a href="#menu">Menu</a>
        <a href="#order">Order Now</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="menu">
        <h2>Our Menu</h2>
        <p>All items are vegetarian-friendly. Prices are reasonable and include taxes.</p>
        <div class="menu-item">
            <img src="https://picsum.photos/300/200?random=1" alt="Pizza">
            <h3>Margherita Pizza</h3>
            <p>Tomato, mozzarella, basil. $12</p>
        </div>
        <div class="menu-item">
            <img src="https://picsum.photos/300/200?random=2" alt="Fries">
            <h3>Crispy Fries</h3>
            <p>Golden and salty. $5</p>
        </div>
        <div class="menu-item">
            <img src="https://picsum.photos/300/200?random=3" alt="Burger">
            <h3>Veggie Burger</h3>
            <p>Lettuce, tomato, cheese. $10</p>
        </div>
        <div class="menu-item">
            <img src="https://picsum.photos/300/200?random=4" alt="Salad">
            <h3>Garden Salad</h3>
            <p>Mixed greens, veggies, dressing. $8</p>
        </div>
        <div class="menu-item">
            <img src="https://picsum.photos/300/200?random=5" alt="Wrap">
            <h3>Veggie Wrap</h3>
            <p>Spinach, hummus, veggies. $9</p>
        </div>
        <div class="menu-item">
            <img src="https://picsum.photos/300/200?random=6" alt="Pasta">
            <h3>Pesto Pasta</h3>
            <p>Basil pesto, cherry tomatoes. $11</p>
        </div>
    </section>
    
    <section id="order">
        <h2>Order Now</h2>
        <p>Choose home delivery or take away. We'll confirm via phone.</p>
        <form class="order-form" id="orderForm">
            <label for="name">Your Name:</label>
            <input type="text" id="name" required>
            
            <label for="item">Select Item:</label>
            <select id="item" required>
                <option value="">Choose...</option>
                <option value="Margherita Pizza - $12">Margherita Pizza - $12</option>
                <option value="Crispy Fries - $5">Crispy Fries - $5</option>
                <option value="Veggie Burger - $10">Veggie Burger - $10</option>
                <option value="Garden Salad - $8">Garden Salad - $8</option>
                <option value="Veggie Wrap - $9">Veggie Wrap - $9</option>
                <option value="Pesto Pasta - $11">Pesto Pasta - $11</option>
            </select>
            
            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" min="1" required>
            
            <label for="option">Delivery Option:</label>
            <select id="option" required>
                <option value="Home Delivery">Home Delivery</option>
                <option value="Take Away">Take Away</option>
            </select>
            
            <label for="address">Address (for delivery):</label>
            <input type="text" id="address">
            
            <button type="submit">Place Order</button>
        </form>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>For inquiries or orders, reach out to:</p>
        <p><strong>Chirag Jain</strong></p>
        <p>Phone: +1 (123) 456-7890</p>
        <p>Email: chirag.jain@cafe.com</p>
    </section>
    
    <footer>
        <p>&copy; 2023 Chirag's Cafe. All rights reserved.</p>
    </footer>
    
    <script>
        document.getElementById('orderForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Order placed! We\'ll contact you soon.');
            // In a real site, this would send data to a server.
        });
    </script>
</body>
</html>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Enable GitHub Pages

_Welcome to GitHub Pages and Jekyll :tada:!_

The first step is to enable GitHub Pages on this [repository](https://docs.github.com/en/get-started/quickstart/github-glossary#repository). When you enable GitHub Pages on a repository, GitHub takes the content that's on the main branch and publishes a website based on its contents.

### :keyboard: Activity: Enable GitHub Pages

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Under your repository name, click **Settings**.
1. Click **Pages** in the **Code and automation** section.
1. Ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu.
1. Click the **Save** button.
1. Wait about _one minute_ then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
   > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.
   > **Note**: In the **Pages** of **Settings**, the **Visit site** button will appear at the top. Click the button to see your GitHub Pages site.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
