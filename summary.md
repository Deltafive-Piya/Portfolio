<span style="color:yellow;">things to consider when building...</span>

- <span style="color:white;">GitHub Pages:</span> GitHub Pages is a free hosting service provided by GitHub.
    - <span style="color:white;">Responsive Design:</span> Ensure your web application is responsive and serves appropriately sized images based on the user's device.

- <span style="color:white;">Third-Party Services:</span> If you use a service like <span style="color:yellow;">Netlify</span> or <span style="color:yellow;">Vercel</span>, they often integrate with GitHub and provide more flexibility than GitHub Pages. 
    - These services allow you to run <span style="color:yellow;">serverless functions</span>, which can help optimize media delivery. 
    - Additionally, they offer built-in features for <span style="color:yellow;">image optimization</span> and <span style="color:yellow;">lazy loading</span>.

        - <span style="color:yellow;">Image Optimization:</span> Compressed images, appropriate formats, and responsive design to serve the right image size based on the user's device.

        - <span style="color:yellow;">Lazy Loading:</span> Implement lazy loading to load images as the user scrolls, reducing the initial page load time.

- <span style="color:white;">Content Delivery:</span> For optimal media loading on GitHub or any other platform, consider integrating a Content Delivery Network (CDN) if your audience is global.
    - <span style="color:white;">CDNs can cache and deliver media files from servers closer to the user's location, reducing latency.</span>

- <span style="color:white;">Monitoring:</span> After deployment, use web performance monitoring tools to check the loading times and user experience. 
    - Tools like Lighthouse, WebPageTest, and Google PageSpeed Insights can help identify areas for improvement.