<body>
    <div class="container">
        <header class="project-header">
            <p class="project-title">EMSA-Net</p>
            <div class="project-meta">
                <div class="meta-item">
                    <i class="fas fa-calendar-alt"></i>
                    <span>2025-05-06</span>
                </div>
                <div class="meta-item">
                    <i class="fas fa-tags"></i>
                    <span>AITC论文</span>
                </div>
            </div>
        </header>
        <main class="project-content">
            <section class="section">
                <h2 class="section-title">
                    <i class="fas fa-quote-left"></i>
                    <span>摘要</span>
                </h2>
                <div class="intro-card">未合理装载或遮盖卡车的货物洒漏问题是导致交通事故的重要因素。在城市道路上检测洒漏风险车辆对于主动交通安全管理至关重要，但该任务面临着目标尺度剧烈变化和严重的边界模糊问题，尤其在夜间低光照环境下更为突出。现有检测器在处理这一特定任务时，往往难以平衡检测精度与效率。为应对这些挑战，我们提出了 EMSA-Net（高效多尺度与边界感知网络，Efficient Multi-scale and Boundary-Aware Network）。该框架包含两个具有协同作用的新型组件：（1）高效多尺度卷积（EMSC）模块，能够以最小的计算开销提取丰富特征；（2）选择性边界聚合（SBA）模块，可自适应地将高分辨率边界线索与强语义信息进行融合。这种双重注意力融合机制显著提升了对光照条件不佳目标的定位精度。大量实验表明，EMSA-Net 的性能显著优于现有主流模型。具体而言，在 UrbanTruck-24H 数据集上，EMSA-Net 实现了 71.8% 的 mAP@0.5（平均精度均值 @0.5）和 92 FPS（帧率），相较于性能强劲的 YOLOv8-m 基准模型，精度提升了 3.2%。可视化结果进一步证实了该模型的有效性与可解释性，充分展现了其在洒漏风险车辆检测任务中具备稳健且精准的检测能力。
                </div>
                <div class="intro-card">Cargo spillage from improperly loaded or covered trucks, here termed Spillage Risk Vehicles (SRVs), is a significant 
contributor to traffic accidents. The detection of SRVs on urban roads is crucial for proactive traffic safety 
management, yet this task is confronted by drastic variations in target scale and severe boundary ambiguity, 
especially under low-light nighttime conditions. Existing detectors often struggle to balance accuracy and efficiency 
for this specialized task. To address these challenges, we propose EMSA-Net : an Efficient Multi-scale and BoundaryAware Network. Our framework introduces two novel and synergistic components: (1) an Efficient Multi-Scale 
Convolution (EMSC) module, which extracts rich features with minimal computational overhead; and (2) a Selective 
Boundary Aggregation (SBA) module, which adaptively fuses high-resolution boundary cues with strong semantic 
information. This dual-attention fusion significantly enhances localization accuracy for poorly illuminated targets. 
Extensive experiments demonstrate that EMSA-Net significantly outperforms existing state-of-the-art models. 
Specifically, on UrbanTruck-24H dataset, EMSA-Net achieves 71.8% mAP@0.5 with 92 FPS, outperforming the 
strong YOLOv8-m baseline by 3.2%. Visualizations further corroborate the model’s effectiveness and 
interpretability, showcasing its capability in robust and precise Spillage Risk Vehicle Detection.
                </div>
            </section>
            <section class="section">
                <h2 class="section-title">
                    <i class="fas fa-camera"></i>
                    <span>相关图片</span>
                </h2>
                <div class="photo-gallery">
                    <div class="photo-item"> 
                    <img src="../assets/pro31.jpg" alt="项目演示照片" >
                    </div>
                    <div class="photo-item"> 
                    <img src="../assets/pro33.jpg" alt="项目演示照片" >
                    </div>
                    <div class="photo-item"> 
                    <img src="../assets/pro36.jpg" alt="项目演示照片" >
                    </div>
                </div>
            </section>
            <section class="section">
                <h2 class="section-title">
                    <i class="fas fa-camera"></i>
                    <span>会议汇报</span>
                </h2>
                  <div class="grid cards" markdown>
                   <iframe src="../../ESMA-Net.pdf" width="100%" height="800px" style="border: 1px solid #ccc; overflow: auto;">
                   </iframe>
                  </div>
            </section>
        </main>
    </div>
</body>