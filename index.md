---
layout: home
title: sGRIPPER v.1
---

<style>
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .animate-section {
    animation: fadeInUp 1s ease-out forwards;
    opacity: 0;
  }

  body {
    background: #e0f2fe; /* Light Blue Background */
    min-height: 100vh;
    margin: 0;
  }

  .project-card {
    background: linear-gradient(135deg, #2563eb 0%, #1e40af 100%);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 24px;
    padding: 60px;
    box-shadow: 0 25px 50px rgba(0,0,0,0.2);
    max-width: 1100px;
    margin: 0 auto;
  }

  .project-card h2 { color: #ffffff !important; font-size: 2.8rem; font-weight: 800; text-align: center; margin-bottom: 50px; letter-spacing: -0.02em; }
  .project-card p, .project-card div { color: #e0e7ff !important; font-size: 1.2rem; line-height: 1.9; text-align: justify; }
  .project-card b { color: #ffffff !important; font-weight: 700; }
  .project-card h3 { color: #ffffff !important; font-size: 1.8rem; margin-top: 40px; border-left: 4px solid #60a5fa; padding-left: 15px; }

  .img-white-bg {
    background-color: #ffffff;
    padding: 30px;
    border-radius: 20px;
    margin-bottom: 45px;
    text-align: center;
    border: 1px solid rgba(255, 255, 255, 0.2);
    box-shadow: inset 0 2px 10px rgba(0,0,0,0.05);
  }

  .cta-button {
    display: inline-block;
    padding: 18px 45px;
    background: #ffffff;
    color: #1e40af !important;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 700;
    font-size: 1.1rem;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    margin-top: 50px;
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  }

  .cta-button:hover {
    transform: scale(1.05) translateY(-2px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
    background: #f8fafc;
  }
</style>

<div style="width: 100%; margin: 0; padding: 100px 20px; font-family: 'Google Sans', -apple-system, sans-serif; box-sizing: border-box;">

  <header class="animate-section" style="text-align: center; margin-bottom: 80px;">
    <h1 style="font-size: 4.5rem; font-weight: 800; color: #1e3a8a; margin-bottom: 10px; letter-spacing: -0.06em;">
      sGRIPPER <span style="color: #3b82f6;">v.1</span>
    </h1>
    <p style="font-size: 1.6rem; color: #60a5fa; font-weight: 400; letter-spacing: 2px; text-transform: uppercase;">BY SANATAN SINHA</p>
  </header>

  <div class="animate-section" style="max-width: 1100px; margin: 0 auto;">
    <section class="project-card">
      <h2>Project Overview</h2>
      
      <div class="img-white-bg">
        <img src="IMG_6587-removebg-preview.png" alt="sGRIPPER v.1 Technical Design" style="width: 100%; max-width: 850px; display: block; margin: 0 auto;">
      </div>

      <div>
        The <b>sGRIPPER v.1</b> is a specialized high-performance robotic end-effector engineered to solve the common pitfalls of traditional 3D-printed and hobbyist grippers. While most low-cost grippers rely on flimsy geared pivots that suffer from immense backlash, the sGRIPPER utilizes an <b>industrial-grade MGN 7 linear rail</b> as its primary guidance system. 
        <br><br>
        This design choice ensures that the fingertips remain perfectly parallel throughout the entire stroke, eliminating the "skewing" effect seen in cheaper rack-and-pinion or pivot-based designs.
      </div>

      <h3>Why Cam-Based Actuation?</h3>
      <div>
        At the heart of the sGRIPPER v.1 is a custom <b>cam-based actuation mechanism</b>. Unlike standard direct-drive grippers where the motor stalls against the object, the cam profile is mathematically optimized to provide a <b>mechanical advantage</b> that increases as the gripper closes. 
        <br><br>
        This allows for significantly higher gripping forces with a smaller motor footprint. Furthermore, the cam system inherently provides <b>self-locking characteristics</b>, meaning the gripper can maintain its hold even if power is modulated, preventing the accidental drop of payloads.
      </div>

      <h3>Superiority Over Conventional Designs</h3>
      <div>
        Most robotic grippers utilize plastic-on-plastic sliding surfaces which create friction and wear over time. By integrating the <b>MGN 7 stainless steel rail</b>, the sGRIPPER v.1 achieves near-zero friction movement. 
        <br><br>
        <b>Key Advantages:</b>
        <ul>
          <li><b>High Precision:</b> The MGN 7 rail provides micron-level accuracy, ensuring repeatable picking of tiny components.</li>
          <li><b>Durability:</b> Steel-on-steel ball bearing movement outlasts traditional geared pivots by a factor of 10x.</li>
          <li><b>Stability:</b> The wide carriage of the rail absorbs side-loading forces, preventing the fingers from twisting when lifting heavy or off-center objects.</li>
        </ul>
      </div>

      <div style="text-align: center;">
        <a href="https://sanrobo206.github.io" class="cta-button">RETURN TO PROJECT HUB</a>
      </div>
    </section>
  </div>

  <footer class="animate-section" style="margin-top: 150px; text-align: center; color: #1e40af; font-size: 1rem; padding-bottom: 60px; text-transform: uppercase; letter-spacing: 3px;">
    Created by <span style="font-weight: 700; color: #1e3a8a;">Sanatan Sinha</span>
  </footer>

</div>
