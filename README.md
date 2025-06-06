 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Tech Automation Learning Hub</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');
  :root {
    --primary-color: #3f51b5;
    --secondary-color: #ff4081;
    --bg-color: #f5f7fa;
    --text-color: #333;
    --header-height: 70px;
  }
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    scroll-behavior: smooth;
  }
  header {
    position: fixed;
    top: 0;
    width: 100%;
    height: var(--header-height);
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 2rem;
    z-index: 1000;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
  }
  header h1 {
    font-weight: 600;
    font-size: 1.8rem;
    letter-spacing: 1px;
    cursor: default;
  }
  nav {
    display: flex;
    gap: 1.5rem;
  }
  nav a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    transition: background-color 0.3s ease;
  }
  nav a:hover, nav a.active {
    background-color: rgba(255, 255, 255, 0.3);
  }
  main {
    max-width: 1100px;
    margin: 0 auto;
    padding: 100px 20px 50px 20px;
  }
  section {
    margin-bottom: 60px;
    background: #fff;
    padding: 30px 40px;
    border-radius: 15px;
    box-shadow: 0 6px 18px rgba(63,81,181,0.1);
  }
  section h2 {
    color: var(--primary-color);
    margin-bottom: 20px;
    font-weight: 600;
    font-size: 2rem;
    border-bottom: 3px solid var(--secondary-color);
    display: inline-block;
    padding-bottom: 5px;
  }
  section p.description {
    font-weight: 300;
    font-size: 1.1rem;
    margin-bottom: 25px;
    color: #555;
  }
  ul.topics {
    list-style: square inside;
    font-size: 1.05rem;
    color: #444;
    line-height: 1.6;
  }
  ul.topics li {
    margin-bottom: 12px;
  }
  /* AI Tools Store Section */
  #ai-tools {
    padding-top: 10px;
  }
  .tools-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 22px;
  }
  .tool-card {
    background: #fafafa;
    border-radius: 12px;
    padding: 16px;
    box-shadow: 0 2px 10px rgba(63,81,181,0.1);
    display: flex;
    flex-direction: column;
    align-items: center;
    transition: transform 0.25s ease;
  }
  .tool-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 10px 20px rgba(63,81,181,0.15);
  }
  .tool-icon {
    width: 70px;
    height: 70px;
    margin-bottom: 14px;
  }
  .tool-name {
    font-weight: 600;
    color: var(--primary-color);
    font-size: 1.15rem;
    margin-bottom: 8px;
    text-align: center;
  }
  .tool-desc {
    font-weight: 300;
    font-size: 0.95rem;
    color: #555;
    text-align: center;
    flex-grow: 1;
  }
  .tool-link {
    margin-top: 15px;
    background-color: var(--secondary-color);
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    padding: 8px 14px;
    border-radius: 20px;
    transition: background-color 0.3s ease;
    user-select: none;
  }
  .tool-link:hover {
    background-color: var(--primary-color);
  }
  /* Responsive adjustments */
  @media (max-width: 600px) {
    main {
      padding: 90px 15px 40px 15px;
    }
    nav {
      gap: 0.8rem;
    }
    nav a {
      padding: 0.4rem 0.8rem;
      font-size: 0.9rem;
    }
  }
  footer {
    text-align:center;
    padding: 25px 10px;
    background: #222;
    color: #ccc;
    font-weight: 300;
    font-size: 0.95rem;
  }
</style>
</head>
<body>
<header>
  <h1>Tech Automation Learning Hub</h1>
  <nav id="nav-menu">
    <a href="#basic-tech" class="active">Basic Tech</a>
    <a href="#digital-marketing">Digital Marketing</a>
    <a href="#web-tech">Web Technology</a>
    <a href="#ai">Artificial Intelligence</a>
    <a href="#medical-code">Medical Code Basics</a>
    <a href="#ai-tools">AI Tools Store</a>
  </nav>
</header>
<main>
  <section id="basic-tech">
    <h2>Basic Technology Course</h2>
    <p class="description">Start your tech journey with foundational knowledge and skills across hardware, software, and computing basics.</p>
    <ul class="topics">
      <li>Introduction to Computers and Operating Systems</li>
      <li>Basic Programming Concepts (Variables, Data Types, Control Flow)</li>
      <li>Understanding Networks and the Internet</li>
      <li>Introduction to Databases and Data Storage</li>
      <li>Cybersecurity Essentials and Safe Computing</li>
    </ul>
  </section>
  <section id="digital-marketing">
    <h2>Digital Marketing</h2>
    <p class="description">Learn the core skills to promote products and services digitally across various platforms and channels.</p>
    <ul class="topics">
      <li>SEO and SEM Fundamentals</li>
      <li>Social Media Marketing Strategies</li>
      <li>Email Marketing Basics and Campaigns</li>
      <li>Google Analytics and Data-Driven Decisions</li>
      <li>Content Marketing and Blogging Essentials</li>
    </ul>
  </section>
  <section id="web-tech">
    <h2>Web Technology</h2>
    <p class="description">Master the technologies behind website creation from front-end scripting to back-end development basics.</p>
    <ul class="topics">
      <li>HTML5, CSS3, and Responsive Design</li>
      <li>JavaScript Fundamentals and DOM Manipulation</li>
      <li>Introduction to Frontend Frameworks (React, Vue, Angular overview)</li>
      <li>Backend Basics: APIs and Databases Overview</li>
      <li>Deploying and Hosting Websites</li>
    </ul>
  </section>
  <section id="ai">
    <h2>Artificial Intelligence</h2>
    <p class="description">Explore AI principles, machine learning concepts, and build a foundation for intelligent applications.</p>
    <ul class="topics">
      <li>Introduction to AI and Machine Learning</li>
      <li>Supervised vs Unsupervised Learning</li>
      <li>Data Preprocessing and Feature Engineering</li>
      <li>Working with Neural Networks and Deep Learning</li>
      <li>AI Ethics and Responsible AI Use</li>
    </ul>
  </section>
  <section id="medical-code">
    <h2>Medical Code Basics</h2>
    <p class="description">Understand medical coding fundamentals essential for healthcare documentation and billing systems.</p>
    <ul class="topics">
      <li>Introduction to Medical Coding Systems: ICD, CPT, HCPCS</li>
      <li>Basics of Medical Terminology</li>
      <li>Understanding Healthcare Data Privacy (HIPAA overview)</li>
      <li>Electronic Health Records (EHR) Systems Overview</li>
      <li>Medical Billing and Claims Process Basics</li>
    </ul>
  </section>
  <section id="ai-tools">
    <h2>AI Tools Store</h2>
    <p class="description">Explore and access popular AI tools from a single place, helping you boost productivity and creativity.</p>
    <div class="tools-grid" id="toolsGrid">
      <!-- Tool cards dynamically inserted here -->
    </div>
  </section>
</main>
<footer>
  &copy; 2024 Tech Automation Learning Hub &nbsp;|&nbsp; All rights reserved.
</footer>
<script>
  // Navigation active link highlight on scroll
  const sections = document.querySelectorAll('section');
  const navLinks = document.querySelectorAll('nav a');
  window.addEventListener('scroll', () => {
    let current = '';
    sections.forEach(section => {
      const sectionTop = section.offsetTop - 80;
      const sectionHeight = section.offsetHeight;
      if(pageYOffset >= sectionTop && pageYOffset < sectionTop + sectionHeight) {
        current = section.getAttribute('id');
      }
    });
    navLinks.forEach(link => {
      link.classList.remove('active');
      if(link.getAttribute('href').substring(1) === current) {
        link.classList.add('active');
      }
    });
  });

  // AI Tools data
  const aiTools = [
    {
      name: "ChatGPT",
      description: "Advanced conversational AI by OpenAI for chat, writing, and coding assistance.",
      url: "https://chat.openai.com/",
      icon: "https://cdn-icons-png.flaticon.com/512/1384/1384060.png"
    },
    {
      name: "DALL·E",
      description: "AI image generation from natural language prompts by OpenAI.",
      url: "https://openai.com/dall-e/",
      icon: "https://cdn-icons-png.flaticon.com/512/565/565547.png"
    },
    {
      name: "Google AI",
      description: "Google's AI platform offering ML tools, research, and APIs.",
      url: "https://ai.google/",
      icon: "https://cdn-icons-png.flaticon.com/512/888/888847.png"
    },
    {
      name: "Hugging Face",
      description: "Open source AI model hub for NLP, vision, and audio models.",
      url: "https://huggingface.co/",
      icon: "https://cdn-icons-png.flaticon.com/512/888/888879.png"
    },
    {
      name: "RunwayML",
      description: "Creative tools for video, art, and media powered by AI.",
      url: "https://runwayml.com/",
      icon: "https://runwayml.com/favicon.ico"
    },
    {
      name: "TensorFlow",
      description: "Open source machine learning framework by Google.",
      url: "https://www.tensorflow.org/",
      icon: "https://cdn-icons-png.flaticon.com/512/5968/5968322.png"
    },
    {
      name: "IBM Watson",
      description: "AI-powered APIs and solutions by IBM for enterprises.",
      url: "https://www.ibm.com/watson",
      icon: "https://cdn-icons-png.flaticon.com/512/888/888859.png"
    },
    {
      name: "Microsoft Azure AI",
      description: "Comprehensive AI services and tools by Microsoft Azure.",
      url: "https://azure.microsoft.com/en-us/services/cognitive-services/",
      icon: "https://azurecomcdn.azureedge.net/cvt-ecd477b348dd8519a19d5e21a7a2efcee3cec3e8a7f858504a8419317c1b4b39/svg/ai-icon.svg"
    },
    {
      name: "OpenCV",
      description: "Open source computer vision library used widely to build AI vision applications.",
      url: "https://opencv.org/",
      icon: "https://opencv.org/wp-content/uploads/2020/07/OPENCV.png"
    }
  ];

  // Populate AI tools grid
  const grid = document.getElementById('toolsGrid');
  aiTools.forEach(tool => {
    const card = document.createElement('div');
    card.className = 'tool-card';
    const icon = document.createElement('img');
    icon.className = 'tool-icon';
    icon.src = tool.icon;
    icon.alt = tool.name;
    icon.onerror = () => {icon.style.display='none'}; // hide icon if fails to load
    const name = document.createElement('div');
    name.className = 'tool-name';
    name.textContent = tool.name;
    const desc = document.createElement('div');
    desc.className = 'tool-desc';
    desc.textContent = tool.description;
    const link = document.createElement('a');
    link.className = 'tool-link';
    link.href = tool.url;
    link.target = '_blank';
    link.rel = 'noopener noreferrer';
    link.textContent = 'Visit';
    card.appendChild(icon);
    card.appendChild(name);
    card.appendChild(desc);
    card.appendChild(link);
    grid.appendChild(card);
  });
</script>
</body>
</html>

