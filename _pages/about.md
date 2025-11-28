---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# 😄 About Me

I have been a Ph.D. candidate at the School of Integrated Circuits, [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/), since September 2022, under the supervision of [Prof. Lei He](https://scholar.google.com/citations?user=n_N-PJkAAAAJ&hl=en). I am also a research intern at the [Eastern Institute of Technology (EIT), Ningbo](https://www.eitech.edu.cn/). Prior to that, I obtained my M.S. degree from [Xidian University](https://www.xidian.edu.cn/), supervised by [Prof. Kang Li](https://faculty.xidian.edu.cn/LK4/zh_CN/index/348597/list/index.htm).

<div style="margin-top: 10px;">
  <a href="https://github.com/ShaoqiangLu"
     target="_blank"
     style="background-color: #333333; color: white; padding: 5px 10px; border-radius: 4px; font-size: 14px; text-decoration: none; display: inline-block;">
    📄 Download CV
  </a>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <div style="flex: 1; margin-right: 1px;">
    <h2>🎯 Research Interests</h2>
    <ul>
      <li>Digital IC Design for AI Chips</li>
      <li>Hardware/Software Co-Optimization</li>
      <li>AI Compiler Development</li>
      <li>FPGA-Based Accelerator</li>
      <li>AI Models:Llama,dLLM,Mamba,VLA</li>
    </ul>
  </div>

  <div style="flex: 1; margin-left: 1px;">
    <h2>🎓 Education</h2>
    <ul>
      <li>
        <strong>Shanghai Jiao Tong University</strong> (2022.09 – 2026.06)<br>
        <em>Ph.D. in Integrated Circuits Engineering</em>
      </li>
      <li>
        <strong>Xidian University</strong> (2019.09 – 2022.06)<br>
        <em>Master’s in Integrated Circuit Design</em>
      </li>
      <li>
        <strong>Xidian University</strong> (2015.09 – 2019.06)<br>
        <em>Bachelor’s in Integrated Circuit Design and Systems</em>
      </li>
    </ul>
  </div>
</div>

# 🏆 Awards
- *2025.11*: &nbsp;🏅 1st Prize, the [Build Your Dreams (BYD) Scholarship](https://icisee.sjtu.edu.cn/xsgz-gzzd-xssw/2896.html), Shanghai Jiao Tong University — Rank 3/160, RMB 20,000 
- *2021.12*: &nbsp;🥉 3rd Prize, the [4th "Huawei Cup" China Graduate Chip Innovation Competition](https://mp.weixin.qq.com/s/QNniK5mCp-8QDefy76pcvw?click_id=3), Special First Prize [GalaxyCore Technology Co., Ltd](https://www.gcoreinc.com)
- *2021.7*: &nbsp;🏅 3rd Prize, the [5th National College Student Integrated Circuit Innovation and Entrepreneurship Competition](https://mp.weixin.qq.com/s/YmRTIPAixgHDdzAKwW1xrA)— Northwest Region
- *2020.10*: &nbsp;🥈 2nd Prize, the [3rd "Huawei Cup" China Graduate Chip Innovation Competition](https://mp.weixin.qq.com/s/AwZsIw1SNVQMaqknOuSJHg?click_id=2), Special First Prize [S2C Technology Co., Ltd](https://www.s2ceda.com/ch) 
- *2020.10*: &nbsp;🏅 1st Prize (twice), 2nd Prize (once), Study Excellence Scholarship for Master’s Degree Candidates, Xidian University
- *2019.7*: &nbsp;🎖️ [Excellent Graduate Student Cadre Honor](https://mp.weixin.qq.com/s/WkrwyTyQpA5vGbMlmOAL_Q) (thrice) and Outstanding Student Class Monitor (twice), Xidian University

# 📝 Publications 

- [1] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ASPLOS 2026</span> DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU. **<u>Shaoqiang Lu</u>**, Yangbo Wei, Junhong Qian, Dongge Qin, Shiji Gao, Yizhi Ding, Qifan Wang, Chen Wu, Xiao Shi, Lei He.

<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  
  <a href="javascript:void(0);" style="pointer-events: none; text-decoration: none;">
    <button style="border: 1px solid #ccc; color: #999; background-color: #f5f5f5; padding: 2px 6px; border-radius: 4px; cursor: not-allowed; font-size: 12px;">
      PDF
    </button>
  </a>
  <!--
  <a href="_pages/paper/DATE2025.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
    <a href="https://youtu.be/6DrQbjT2kXI" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>-->
</div>



- [2] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">DAC 2025</span> MambaOPU: An FPGA Overlay Processor for State-space-duality-based Mamba Models. **<u>Shaoqiang Lu</u>**, Xuliang Yu, Tiandong Zhao, Siyuan Miao, Xinsong Sheng, Chen Wu, Liang Zhao, Ting-Jung Lin, Lei He.

<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  
  <a href="https://ieeexplore.ieee.org/document/11132895" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/ICCAD2024.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  -->
</div>




- [3] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ICCAD 2025</span> MoE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-based Large Language Models. **<u>Shaoqiang Lu</u>**, Yangbo Wei, Junhong Qian, Chen Wu, Xiao Shi, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/ASP-DAC2024.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  -->
</div>

- [4] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">TRETS Journal 2025,ISEDA 2024</span> MCoreOPU: An FPGA-based Multi-Core Overlay Processor for Transformer-based Models. **<u>Shaoqiang Lu</u>**, Tiandong Zhao, Ting-Jung Lin, Rumin Zhang, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://dl.acm.org/doi/10.1145/3742437" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/ICCAD2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/EQ50eG3W36Y" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>

- [5] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ICCAD 2024</span> ChatOPU: An FPGA-based Overlay Processor for Large Language Models with Unstructured Sparsity. Tiandong Zhao, **<u>Shaoqiang Lu</u>**, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://dl.acm.org/doi/10.1145/3676536.3676761" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [6] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ASAP 2025</span> <span style="color:red;">(Best Paper Nomination)</span>METAL: A Memory-Efficient Transformer Architecture for Long-Context Inference on FPGA. Zicheng He, **<u>Shaoqiang Lu</u>**, Tiandong Zhao, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/11113558" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2024.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/ZJqte7cuPhk" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [7] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ASP-DAC 2026</span> dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models. Yangbo Wei, **<u>Shaoqiang Lu</u>**, Junhong Qian, Chen Wu, Xiao Shi, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [8] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">AAAI 2026</span> Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM Inference. Yangbo Wei, Zhen huang, **<u>Shaoqiang Lu</u>**, Junhong Qian, Dongge Qin, Ting Jung Lin, WEI W. XING, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [9] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">FPL 2023</span> Token Packing for Transformers with Variable-Length Inputs. Tiandong Zhao, Siyuan Miao, **<u>Shaoqiang Lu</u>**, Jialin Cao, Jun Qiu, Xiao Shi, Kun Wang, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/10296372" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [10] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">FCCM 2025</span> C2OPU: Hybrid Compute-in-Memory and Coarse-Grained Reconfigurable Architecture for Overlay Processing of Transformers. Siyuan Miao, Lingkang Zhu, Chen Wu, **<u>Shaoqiang Lu</u>**, Jinming Lyu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/11008948" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>



- [11] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">Science China: Information Sciences 2025</span> FPGA Overlay processor for AI computing. He Lei, Wang Kun, Wu Chen, Tao Zhuofu, Shi Xiao, Miao Siyuan, **<u>Shaoqiang Lu</u>**.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://www.sciengine.com/SSI/doi/10.1360/SSI-2024-0351" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


