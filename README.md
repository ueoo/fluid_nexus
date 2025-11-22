# FluidNexus: Monocular 3D Fluid Reconstruction and Predictionand Its Application in Two-Phase Fluid

> https://yuegao.me/fluid_nexus/

## Abstract
We study reconstructing and predicting 3D fluid appearance and velocity from a single video. Current methods require multi-view videos for fluid reconstruction. We present \model, a novel framework that bridges video generation and physics simulation to tackle this task. Our key insight is to synthesize multiple novel-view videos as references for reconstruction. \model consists of two key components: (1) a novel-view video synthesizer that combines frame-wise view synthesis with video diffusion refinement to generate realistic videos, and (2) a physics-integrated particle representation that can be incorporated to generate differentiable simulation and rendering to simultaneously facilitate 3D fluid reconstruction and prediction. To evaluate our approach, we collect two real-world smoke datasets featuring textured backgrounds and object interactions, as well as a two-phase liquid-vapor flow dataset. Our method enables dynamic novel view synthesis, future prediction, and interaction simulation from a single fluid video.
