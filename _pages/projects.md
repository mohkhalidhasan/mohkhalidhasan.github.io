---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
description: Selected ongoing research projects in wireless communications, cybersecurity, trustworthy AI, and intelligent networked systems.
---

<style>
  .projects-intro {
    font-size: 1.02rem;
    line-height: 1.7;
    margin-bottom: 1.8rem;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin: 1rem 0 2rem;
  }

  .project-card {
    background: var(--global-card-bg-color, transparent);
    border: 1px solid var(--global-divider-color, #d8d8d8);
    border-radius: 12px;
    padding: 1.15rem 1.2rem;
    transition:
      transform 0.2s ease,
      box-shadow 0.2s ease;
  }

  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.10);
  }

  .project-card h3 {
    color: var(--global-theme-color, #450084);
    font-size: 1.05rem;
    line-height: 1.4;
    margin: 0 0 0.6rem;
  }

  .project-card p {
    font-size: 0.93rem;
    line-height: 1.6;
    margin: 0;
  }

  @media (max-width: 760px) {
    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="projects-intro">
This page highlights selected ongoing and recent research projects. The projects focus on practical problems in wireless security, trustworthy machine learning, intelligent communications, and resilient networked systems.
</div>

<div class="project-grid">

  <div class="project-card">
    <h3>Federated Learning Security Against Jamming-Assisted Insider Attacks</h3>
    <p>
      Studies how malicious federated-learning participants can exploit wireless
      jamming and unfavorable channel conditions to conceal poisoned model updates.
      The project develops attack models and robust aggregation and detection
      mechanisms that incorporate wireless-side information.
    </p>
  </div>

  <div class="project-card">
    <h3>Federated Learning for UAV/GNSS Spoofing Detection</h3>
    <p>
      Investigates secure collaborative learning for detecting GPS/GNSS spoofing
      in UAV and distributed wireless systems. The work examines malicious clients,
      label manipulation, model poisoning, and defenses that combine statistical
      evidence with physical-context information.
    </p>
  </div>

  <div class="project-card">
    <h3>Energy-Aware Physical-Layer Security for Resource-Constrained IoT Networks</h3>
    <p>
      Develops adaptive physical-layer security techniques for protecting IoT
      wireless transmissions against eavesdropping while limiting energy
      consumption. The work studies channel conditions, resource allocation,
      artificial noise and cooperative jamming, and security-energy tradeoffs.
    </p>
  </div>

  <div class="project-card">
    <h3>Machine Learning-Based RF Fingerprinting and Wireless Authentication</h3>
    <p>
      Investigates identification and authentication of wireless devices using
      physical-layer RF characteristics. The work considers reliable device
      recognition under changing channels, hardware variability, interference,
      and adversarial conditions.
    </p>
  </div>

  <div class="project-card">
    <h3>Mental Health Prediction Using Machine Learning and Social Media Data</h3>
    <p>
      Develops machine-learning approaches for identifying indicators of depression
      and related mental-health conditions from social-media data. The project
      examines linguistic, behavioral, and temporal features, with emphasis on
      limited data, model generalization, and reliable prediction.
    </p>
  </div>

  <div class="project-card">
    <h3>NOMA-Based Cognitive Radio Networks and Physical-Layer Security</h3>
    <p>
      Investigates NOMA-enabled cognitive radio systems that improve spectrum
      utilization while maintaining secure communication in the presence of
      untrusted users and eavesdroppers. The work includes channel-aware power
      allocation, cooperative jamming, reverse SIC, secrecy analysis, and
      optimization under different wireless channel conditions.
    </p>
  </div>

  <div class="project-card">
    <h3>Machine Learning-Based Wireless Channel Prediction and Adaptive Beamforming</h3>
    <p>
      Uses LSTM, GRU, BiLSTM, and attention-based models to predict time-varying
      wireless channels. Predicted channel-state information is incorporated into
      ZF, MRT, RZF, MMSE, and related beamforming strategies to study performance
      under delayed or imperfect CSI.
    </p>
  </div>

  <div class="project-card">
    <h3>Security and Intelligent Resource Allocation for Advanced Wireless Networks</h3>
    <p>
      Develops analytical, optimization-based, and learning-assisted security
      techniques for NOMA, MIMO, UAV-assisted, RIS/STAR-RIS, and spectrum-sharing
      networks. The research focuses on secrecy performance, power allocation,
      cooperative communication, artificial noise, and intelligent resource
      optimization.
    </p>
  </div>

</div>
