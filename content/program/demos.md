---
title: "Demo"
draft: false
---
<!--  How to test webpage locally? Execute "hugo server" in the root folder -->

# ICAPS-25 System Demonstrations

<style>
.paper-entry {
    width: 100%;
    padding: 1%;
    font-family: sans-serif;
}
.paper-layout {
    display: flex;
    gap: 1%;
    align-items: flex-start;
    flex-wrap: wrap;
}
.media-column {
    flex: 1 1 55%;
    display: flex;
    flex-direction: column;
    gap: 1%;
}
.teaser {
    border: 1px solid #ccc;
    /* opacity: 0.85; */
    border-radius: 6px;
    text-align: center;
    padding: 0.5%;
}
.full-video {
    border: 2px solid orange;
    border-radius: 6px;
    text-align: center;
    padding: 0.5%;
    background: #fffbe6;
    box-shadow: 0 0 8px rgba(255,165,0,0.3);
}
.teaser img,
.teaser video,
.full-video iframe,
.full-video video {
    width: 100%;
    aspect-ratio: 16/9;
    border-radius: 6px;
}
.caption {
    margin-top: 4px;
    font-size: 0.9em;
    color: #444;
    font-weight: bold;
}
.text-column {
    flex: 1 1 40%;
    padding: 1%;
}
@media (max-width: 800px) {
    .paper-layout {
        flex-direction: column;
    }
    .media-column, .text-column {
        width: 100%;
    }
}
</style>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_8.pdf">Towards Unstructured MAPF: Multi-Quadruped MAPF Demo (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <video controls="" style="width:100%; border-radius: 3%; vertical-align: middle;">
                 <source src="demo8.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                 </source>
                </video>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/ihVPEsN58t0" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo8">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> Multi-Agent Path Finding (MAPF) in its most broad perspective focuses on finding collision free paths for general teams of agents in a shared environment. Theoretically, MAPF methods could solve a variety of multi-agent problems. However, MAPF research primarily focuses on simplified warehouse domains, i.e., gridworld with discrete spaces, discrete timesteps, and point-mass agents without kinematic constraints. Thus, the perception of MAPF is tied closely to gridworld and its assumptions, which limits its attractiveness to more broad domains.</p>
            <b>Authors:</b> Rishi Veerapaneni, Nikhil Sobanbabu, Guanya Shi, Jiaoyang Li, Maxim Likhachev.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_4.pdf">Planning-based Toolchain for Automated Regression Testing of Video Games (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/LfONhR1I8zw" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video -demo4">
                </iframe>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/VrN-Fv56fo4" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo4">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> Regression video game testing, in a nutshell, deals with testing whether the game mechanics implemented in the game maintain their functionality even after updating the game code. Usually, regression testing is performed using test scripts. While effective, they require manual creation and frequent updates throughout development, making the process labor-intensive and error-prone. Automated planning can mitigate this burden by automatically generating and maintaining test scripts, as game mechanics can be specified in a planning domain model using the Planning Domain Definition Language (PDDL). Individual tests then need to specify initial states and goals. This demonstration presents a toolchain that allows for easy integration of planning into a game engine, executing and evaluating specified tests, and collecting detailed logs, telemetry data, and video recordings, allowing users to review test results efficiently.</p>
            <b>Authors:</b> Tomas Balyo, Roman Barták, Tomas Bily, Lukáš Chrpa, Martin Capek, Michal Cervenka, Filip Dvorak, Stephan Gocht, Lukas Lipcak, Viktor Macek, Dominik Rohacek, Josef Ryzi, Martin Suda, Dominik Safranek, Slavomir Svancar, Michael Youngblood.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_1.pdf">PDDL-GenAI -- A Plugin for LLM-Based Support in Planning Domain Modeling (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/2tQgONu1mtA" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo1">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> We aim to facilitate the integration of novel modeling approaches that leverage foundation models to translate natural language descriptions (NLDs) into PDDL. We lower the barrier to access symbolic planners by deploying the NLD-to-PDDL pipeline from Huang, Lipovetzky, and Cohn (2025) as a plugin extension for editor.planning.domains, a PDDL development environment widely used for educational and research purposes. This plugin enables users to provide a template domain and problem file, in which a foundation model populates the action schemas based on NLDs. As many other techniques exist for NLD-to-PDDL translation, we hope this plugin serves as an example of how such approaches can be integrated with existing planning development tools.</p>
            <b>Authors:</b> Jinbiao Wang, Rui Peng, Tong Chen, Chaowen Zeng, Weilin Wang, Sukai Huang, Nir Lipovetzky.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_2.pdf">HDDL Parser: A Realtime Hierarchical Planning Language Validation Toolkit (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <img src="demo2.png" style="width:100%; border-radius: 3%; vertical-align: middle;"/>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/hRZ21HmcEQU" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo2">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> We present HDDL Parser, an open-source language server providing real-time validation for the Hierarchical Planning Domain Definition Language (HDDL). The toolkit implements the well-known Language Server Protocol (LSP), enabling integration into any IDE, with a provided VS Code client demonstrating seamless real-time error detection and correction feedback. The language server performs a comprehensive analysis including: syntax validation, parameter inconsistencies, undefined entities, duplicate definitions, cyclic hierarchies, contradictory formulae, and type checking. Implemented in Rust, the correctness of the HDDL Parser has been validated against all 33 domains from the hierarchical track of the IPC 2023, and even detected critical errors in one of those domains. By providing automated quality assurance directly within the development environment, this tool significantly reduces debugging time and improves model reliability for hierarchical planning applications.</p>
            <b>Authors:</b> Mohammad Yousefi, Pascal Bercher.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_3.pdf">Graphical Navigation in Solution Spaces using PlanPilot (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/stovYamkur0" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo3">
                </iframe>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/75UngGNr5bc" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo3">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> Many planning applications require not only a single solution but benefit substantially from having a set of possible plans from which users can select according to preferences. Surprisingly, planning research has primarily focused on quickly finding single plans for decades. Only recently have researchers started to investigate plan enumeration by top-k planning, offering more flexibility to the user. But simply enumerating the k best plans is far from targeted due to the time-consuming nature of enumeration, likely feeding many similar plans to the user, and forcing the user to define filters beforehand. In fact, in extensive search spaces, enumeration is hardly practical. We present an approach and a tool called PlanPilot to navigate solution spaces of planning tasks iteratively and interactively. We build on answer-set programming (ASP) to restrict the plan space. To that end, we employ facets, which are meaningful actions that appear in some, but not all plans. Enforcing or forbidding such facets allows for navigating even large plan spaces while ensuring desired properties quickly and step by step.</p>
            <b>Authors:</b> Michelle Kornherr, Johannes K. Fichte, Dominik Rusovac, David Speck, Sarah Gaggl, Augusto B. Corrêa, Markus Hecher, Daniel Gnad.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_5.pdf">Dynamic REAP: Bringing Life into Simulations for UAV Planning and Acting Frameworks (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <img src="demo5.png" style="width:100%; border-radius: 3%; vertical-align: middle;"/>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/mthOS7hksZQ" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo5">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> Developing intelligent Unmanned Aerial Vehicles (UAVs)
entails more than ensuring safe navigation; it also involves
equipping them with high-level decision-making abilities
through AI planning. Simulation-based testing is a necessary
gateway in transitioning research works into operational real-world
UAV missions.We demonstrate Dynamic REAP, a simulation
environment that considers accurate physics of the vehicle,
while providing georeferenced semantic segmentation
and tools to include dynamic background characters, removing
thereby the assumption of a static world when used for
validating planning and acting methods. A system demonstration
based on a Search and Rescue (SAR) scenario can be
found at:https://www.youtube.com/watch?v=mthOS7hksZQ</p>
            <b>Authors:</b> Kai Sommer, Björn Döschl, Jane Jean Kiam.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_6.pdf">An LLM-powered Collaborative Numeric Task Planning Framework (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <img src="demo6.jpg" style="width:100%; border-radius: 3%; vertical-align: middle;"/>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <video controls="" style="width:100%; border-radius: 3%; vertical-align: middle;">
                 <source src="demo6-full.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                 </source>
                </video>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> We demonstrate an innovative collaborative planning framework that enables human users to leverage their intuition and domain expertise to intuitively guide automated planning without time-consuming programming expert interventions. We propose an LLM-based pipeline to translate human natural language constraints into formal hard trajectory constraints. The initial user input is refined and decomposed into more explicit constraints before being encoded into PDDL3. The user can also interact with the system in an open dialog to get insights on the problem and current solution, if existing. The system can also retrieve relevant information to identify risks of failure and make suggestions. This integration with an automated planner, a graphical interface and PDSim creates a closed loop that enables users to explore specific alternatives, dynamically refine solutions, and speed up problem solving. Demo Video Link: https://bit.ly/llm-cai</p>
            <b>Authors:</b> Anthony Favier, Ngoc La, Pulkit Verma, Julie Shah.
        </div>
    </div>
</div>

<hr>

<div class="paper-entry">
    <h4><strong><a href="../demos-pdfs/ICAPS25-Demo_paper_9.pdf">Advancing MAPF towards the Real World: A Scalable Multi-Agent Realistic Testbed (SMART) (PDF)</a></strong></h4>
    <div class="paper-layout">
        <div class="media-column">
            <div class="teaser">
                <video controls="" style="width:100%; border-radius: 3%; vertical-align: middle;">
                 <source src="demo9.mp4" type="video/mp4">
                  Your browser does not support the video tag.
                 </source>
                </video>
                <div class="caption">Teaser</div>
            </div>
            <div class="full-video">
                <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen frameborder="0" referrerpolicy="strict-origin-when-cross-origin" src="https://www.youtube.com/embed/irtFxMjyJXs" style="width:100%; aspect-ratio:16/9; border-radius: 3%;" title="YouTube video - demo9">
                </iframe>
                <div class="caption"><strong>Full video</strong></div>
            </div>
        </div>
        <div class="text-column">
            <p><strong>Abstract:</strong> State-of-the-art algorithms for Multi-Agent Path Finding (MAPF) can plan paths for many robots in seconds. However, they often rely on simplified models, making their real-world performance unclear. Bridging the gap is difficult, as accurate evaluations require complex setups and access to large fleets of physical robots. To tackle these challenges, we present Scalable Multi-Agent Realistic Testbed (SMART): a software tool for evaluating the potential of Multi-Agent Path Finding (MAPF) algorithms in realistic environments. SMART connects simplified MAPF solvers with an execution framework based on Action Dependency Graphs. The combination allows seamless integration with complex robot simulators that account for continuous time, kinodynamics, communication delays, and execution uncertainties. It lowers barriers for researchers and enables, for the first time, large-scale MAPF evaluations in physics-based simulations with up to thousands of simultaneous robots.</p>
            <b>Authors:</b> Jingtian Yan, Kevin Zheng, Zhifei Li, William Kang, Yulun Zhang, Zhe Chen, Yue Zhang, Daniel Harabor, Stephen Smith, Jiaoyang Li.
        </div>
    </div>
</div>

<hr>