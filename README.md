# Web3 AI LAB (프로젝트 설계)

## Dr. Jenny: VoiceToVoice Agent

This project outlines the design for Dr. Jenny, a Web3-based AI Voice-to-Voice Agent.

---

### Core Interaction Flow

The primary interaction involves a voice conversation between the user and the Dr. Jenny agent.

<div style="display: flex; align-items: center; justify-content: center; gap: 10px; margin: 20px 0; flex-wrap: wrap;">
  <!-- User Box -->
  <div style="border: 1px solid #ccc; padding: 20px; text-align: center; background-color: #f8f8f8; border-radius: 5px; min-width: 120px;">
    <strong>User</strong><br>Voice
  </div>

  <!-- SVG Arrow -->
  <svg width="100" height="50" viewbox="0 0 100 50" aria-label="Bidirectional arrow">
     <defs>
        <marker id="arrowhead-start" markerWidth="10" markerHeight="7" refX="0" refY="3.5" orient="auto">
          <polygon points="10 0, 10 7, 0 3.5" fill="#555" />
        </marker>
        <marker id="arrowhead-end" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
          <polygon points="0 0, 10 3.5, 0 7" fill="#555" />
        </marker>
      </defs>
      <line x1="10" y1="25" x2="90" y2="25" stroke="#555" stroke-width="2" marker-start="url(#arrowhead-start)" marker-end="url(#arrowhead-end)" />
  </svg>

  <!-- Agent Box -->
  <div style="border: 1px solid #ccc; padding: 20px; text-align: center; background-color: #f8f8f8; border-radius: 5px; min-width: 120px; position: relative;">
    <!-- Placeholder for Agent Visual - Could use an SVG icon or emoji -->
    <div style="font-size: 2em; margin-bottom: 5px;" aria-label="AI Agent Icon">👩‍⚕️</div>
    <strong>Agent</strong><br>Voice<br>(Dr. Jenny)
  </div>
</div>

---

### Supporting Components & Capabilities

Dr. Jenny leverages several key components and areas of knowledge:

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 20px;">

  <!-- EMR Box -->
  <div style="border: 1px solid #ccc; padding: 15px; text-align: left; background-color: #f8f8f8; border-radius: 5px; min-width: 220px;">
    <strong>Electronic Medical Record</strong><br>
    (Blockchain)<br>
    <ul>
        <li>데이터 주권 (Data Sovereignty)</li>
        <li>암호화, 개인키 접근 (Encryption, Private Key Access)</li>
    </ul>
  </div>

  <!-- Coaching Box -->
  <div style="border: 1px solid #ccc; padding: 15px; text-align: center; background-color: #f8f8f8; border-radius: 5px; min-width: 150px; display: flex; flex-direction: column; justify-content: center;">
    <strong>Coaching<br>Counseling<br>Psychology</strong>
  </div>

  <!-- Exercise Box -->
  <div style="border: 1px solid #ccc; padding: 15px; text-align: center; background-color: #f8f8f8; border-radius: 5px; min-width: 150px; display: flex; flex-direction: column; justify-content: center;">
    <strong>Exercise<br>Management</strong>
  </div>

</div>

---

<p align="right" style="font-size: 0.9em; color: #555;">
  모두의연구소
</p>
