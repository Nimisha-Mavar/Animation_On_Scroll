# Implementing Scroll Animations in React with AOS 🎭

![image](https://github.com/user-attachments/assets/52c7719f-7dd9-44da-88ab-97124ea926bf)


This guide explains how to use AOS (Animate On Scroll) for scroll animations in a React application. AOS allows you to animate elements when they come into view as the user scrolls.

### 1️⃣ : Install AOS using npm
    ``` js
    npm install aos
    ```

### 2️⃣ : Import AOS and Styles to app.js
    ``` js 
    import 'aos/dist/aos.css'; // Import AOS styles
    import AOS from 'aos';
    ```

### 3️⃣ : Add Animations to Component
In your React component, use data-aos attributes to specify animation types 
``` js import React from 'react';

    const AnimatedSection = () => {
      return (
        <div className="animated-section" data-aos="fade-up">
          <h2>Animate Me on Scroll!</h2>
        </div>
      );
    };
    
    export default AnimatedSection;
```

### 4️⃣ : Add Animations to Component
### Animation Options
https://michalsnik.github.io/aos/
