<body>
    <div class="container">
        <header class="project-header">
            <p class="project-title">波比陪伴机器人</p>
            <div class="project-meta">
                <div class="meta-item">
                    <i class="fas fa-calendar-alt"></i>
                    <span>2025-03-06</span>
                </div>
                <div class="meta-item">
                    <i class="fas fa-tags"></i>
                    <span>嵌入式课程设计</span>
                </div>
            </div>
        </header>
        <main class="project-content">
            <section class="section">
                <h2 class="section-title">
                    <i class="fas fa-quote-left"></i>
                    <span>设计介绍</span>
                </h2>
                <div class="intro-card">
                    针对日益突出的社会老龄化等问题，本项目设计并实现了一款基于STM32的智能陪伴机器人。</br>
                </div>
                <div class="intro-card">
                主要工作：基于MPU6050传感器与PID算法实现了自平衡与稳定运动，集成循迹及超声波模块完成自主导航与避障；
                    搭建通信与交互层（ESP32-S3）集成麦克风阵列与音频功放，作为语音交互前端连接云端；搭建云端服务与智能决策层，
                    利用WebSocket通信，集成自动语音识别（ASR）、大型语言模型和语音合成技术，处理用户语音、理解意图、生成回应并下达控制指令。
                </div>
            </section>
            <section class="section">
                <h2 class="section-title">
                    <i class="fas fa-camera"></i>
                    <span>照片记录</span>
                </h2>
                <div class="photo-gallery">
                    <div class="photo-item"> 
                    <img src="../assets/pro21.jpg" alt="项目演示照片" >
                    </div>
                </div>
            </section>
            <section class="section">
                <h2 class="section-title">
                    <i class="fas fa-camera"></i>
                    <span>结课汇报</span>
                </h2>
                  <div class="grid cards" markdown>
                   <iframe src="../../波比机器人(2)(1).pdf" width="100%" height="800px" style="border: 1px solid #ccc; overflow: auto;">
                   </iframe>
                  </div>
            </section>
        </main>
    </div>
</body>