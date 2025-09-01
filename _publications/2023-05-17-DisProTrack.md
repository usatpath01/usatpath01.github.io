---
title: "DisProTrack: Distributed Provenance Tracking over Serverless Applications"
collection: publications
permalink: /publication/2023-05-17-DisProTrack
authors: "<b>Utkalika Satapathy</b>, Rishabh Thakur, Subhrendu Chattopadhyay, Sandip Chakraborty"

date: 2023-05-17
venue: '<a href="https://infocom2023.ieee-infocom.org/">IEEE INFOCOM 2023</a>'
paperurl: 'http://usatpath01.github.io/files/disprotrack-infocom2023.pdf'
github: 'https://github.com/usatpath01/DisProTrack'
slides: 'https://drive.google.com/file/d/example-slides-disprotrack/view'
video: 'https://youtube.com/watch?v=example-disprotrack'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<div class="project-header">
  <div class="project-badges">
    <span class="badge badge-conference">IEEE INFOCOM 2023</span>
    <span class="badge badge-year">2023</span>
  </div>
</div>

<div class="project-content">
  <div class="project-overview">
    <h2>📋 Project Overview</h2>
    <p class="lead">Universal Provenance Graph Generation for Serverless Application</p>
    <p>How to detect if a microservice is compromised in a serverless application - <strong>DisProTrack</strong> comes to the rescue! It generates Universal Provenance Graph (UPG) by combining system logs and application logs together for provenance tracking over serverless architecture.</p>
  </div>

  <div class="project-features">
    <h2>🚀 Key Features</h2>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">🔍</div>
        <h3>UPG Design from Logs</h3>
        <p>DisProTrack's Static analyzer module generates the application-specific Log Message String-Control Flow Graph (LMS-CFG) from the application binaries which provides a profile of the application.</p>
      </div>
      
      <div class="feature-card">
        <div class="feature-icon">⚡</div>
        <h3>Runtime Execution Unit Identification</h3>
        <p>DisProTrack has a Linux Loadable Kernel Module (LKM) that can intercept the system calls generated during execution time to identify the semantic relationship between the system logs and the application logs.</p>
      </div>
      
      <div class="feature-card">
        <div class="feature-icon">🎯</div>
        <h3>Improved Search Efficacy</h3>
        <p>Instead of storing the raw log messages in the UPG, we propose conversion and storage of an equivalent regular expression. This method improves the matching accuracy of log messages during the investigation phase and reduces the runtime search complexity by providing a faster response time.</p>
      </div>
      
      <div class="feature-card">
        <div class="feature-icon">🔧</div>
        <h3>Easy Deployment</h3>
        <p>DisProTrack can be deployed as a microservice on top of the SLC without instrumenting the source code of the applications.</p>
      </div>
      
      <div class="feature-card">
        <div class="feature-icon">📊</div>
        <h3>High Performance</h3>
        <p>DisProTrack has a minimal memory footprint (~KB) & responds within 20s-30s.</p>
      </div>
    </div>
  </div>

  <div class="project-team">
    <h2>👥 Research Team</h2>
    <div class="team-grid">
      <div class="team-member">
        <div class="member-avatar">U</div>
        <div class="member-info">
          <h4>Utkalika Satapathy</h4>
          <p>IIT Kharagpur, India</p>
          <span class="member-role">Lead Author</span>
        </div>
      </div>
      
      <div class="team-member">
        <div class="member-avatar">R</div>
        <div class="member-info">
          <h4>Rishabh Thakur</h4>
          <p>IIT Kharagpur, India</p>
          <span class="member-role">Co-Author</span>
        </div>
      </div>
      
      <div class="team-member">
        <div class="member-avatar">S</div>
        <div class="member-info">
          <h4>Subhrendu Chattopadhyay</h4>
          <p>IDRBT Hyderabad, India</p>
          <span class="member-role">Co-Author</span>
        </div>
      </div>
      
      <div class="team-member">
        <div class="member-avatar">S</div>
        <div class="member-info">
          <h4>Sandip Chakraborty</h4>
          <p>IIT Kharagpur, India</p>
          <span class="member-role">Supervisor</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-links">
    <h2>📎 Resources</h2>
    <div class="links-grid">
      <a href="http://usatpath01.github.io/files/disprotrack-infocom2023.pdf" target="_blank" class="resource-link paper-link">
        <i class="fas fa-file-pdf"></i>
        <div class="link-content">
          <h4>Download Paper</h4>
          <p>IEEE INFOCOM 2023</p>
        </div>
      </a>
      
      <a href="https://github.com/usatpath01/DisProTrack" target="_blank" class="resource-link code-link">
        <i class="fab fa-github"></i>
        <div class="link-content">
          <h4>Source Code</h4>
          <p>GitHub Repository</p>
        </div>
      </a>
      
      <a href="https://drive.google.com/file/d/example-slides-disprotrack/view" target="_blank" class="resource-link slides-link">
        <i class="fas fa-file-powerpoint"></i>
        <div class="link-content">
          <h4>Presentation Slides</h4>
          <p>Conference Slides</p>
        </div>
      </a>
      
      <a href="https://youtube.com/watch?v=example-disprotrack" target="_blank" class="resource-link video-link">
        <i class="fab fa-youtube"></i>
        <div class="link-content">
          <h4>Demo Video</h4>
          <p>Project Demonstration</p>
        </div>
      </a>
    </div>
  </div>

  <div class="project-impact">
    <h2>🎯 Impact & Applications</h2>
    <div class="impact-grid">
      <div class="impact-item">
        <h3>🔒 Security</h3>
        <p>Enhanced security monitoring for serverless applications through comprehensive provenance tracking</p>
      </div>
      <div class="impact-item">
        <h3>🐛 Debugging</h3>
        <p>Improved debugging capabilities for distributed microservice architectures</p>
      </div>
      <div class="impact-item">
        <h3>📈 Performance</h3>
        <p>Minimal overhead with fast response times for real-time monitoring</p>
      </div>
      <div class="impact-item">
        <h3>🏗️ Architecture</h3>
        <p>Non-intrusive deployment without requiring source code modifications</p>
      </div>
    </div>
  </div>
</div>

<style>
.project-header {
  margin-bottom: 2rem;
}

.project-badges {
  display: flex;
  gap: 1rem;
  margin-bottom: 1rem;
}

.badge {
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.badge-conference {
  background-color: #e74c3c;
  color: white;
}

.badge-year {
  background-color: #3498db;
  color: white;
}

.project-content {
  max-width: 100%;
}

.project-overview {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 2rem;
  border-radius: 12px;
  margin-bottom: 2rem;
}

.project-overview h2 {
  color: white;
  margin-bottom: 1rem;
}

.project-overview .lead {
  font-size: 1.3rem;
  font-weight: 600;
  margin-bottom: 1rem;
  opacity: 0.9;
}

.project-features h2,
.project-team h2,
.project-links h2,
.project-impact h2 {
  color: #2c3e50;
  border-bottom: 3px solid #3498db;
  padding-bottom: 0.5rem;
  margin-bottom: 1.5rem;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.feature-card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  border-left: 4px solid #3498db;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.15);
}

.feature-icon {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.feature-card h3 {
  color: #2c3e50;
  margin-bottom: 0.8rem;
  font-size: 1.2rem;
}

.feature-card p {
  color: #555;
  line-height: 1.6;
}

.team-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.team-member {
  display: flex;
  align-items: center;
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.team-member:hover {
  transform: translateY(-3px);
}

.member-avatar {
  width: 50px;
  height: 50px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  font-size: 1.2rem;
  margin-right: 1rem;
  flex-shrink: 0;
}

.member-info h4 {
  margin: 0 0 0.3rem 0;
  color: #2c3e50;
  font-size: 1.1rem;
}

.member-info p {
  margin: 0 0 0.3rem 0;
  color: #666;
  font-size: 0.9rem;
}

.member-role {
  background: #ecf0f1;
  color: #2c3e50;
  padding: 0.2rem 0.6rem;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 600;
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.resource-link {
  display: flex;
  align-items: center;
  padding: 1.5rem;
  background: white;
  border-radius: 12px;
  text-decoration: none;
  color: inherit;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  border-left: 4px solid #3498db;
}

.resource-link:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.15);
  text-decoration: none;
  color: inherit;
}

.resource-link i {
  font-size: 2rem;
  margin-right: 1rem;
  color: #3498db;
}

.paper-link { border-left-color: #e74c3c; }
.paper-link i { color: #e74c3c; }

.code-link { border-left-color: #333; }
.code-link i { color: #333; }

.slides-link { border-left-color: #f39c12; }
.slides-link i { color: #f39c12; }

.video-link { border-left-color: #e74c3c; }
.video-link i { color: #e74c3c; }

.link-content h4 {
  margin: 0 0 0.3rem 0;
  color: #2c3e50;
  font-size: 1.1rem;
}

.link-content p {
  margin: 0;
  color: #666;
  font-size: 0.9rem;
}

.impact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.impact-item {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s ease;
}

.impact-item:hover {
  transform: translateY(-3px);
}

.impact-item h3 {
  color: #2c3e50;
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

.impact-item p {
  color: #555;
  line-height: 1.6;
}

/* Mobile responsiveness */
@media (max-width: 768px) {
  .features-grid,
  .team-grid,
  .links-grid,
  .impact-grid {
    grid-template-columns: 1fr;
  }
  
  .project-overview {
    padding: 1.5rem;
  }
  
  .team-member {
    flex-direction: column;
    text-align: center;
  }
  
  .member-avatar {
    margin-right: 0;
    margin-bottom: 1rem;
  }
  
  .resource-link {
    flex-direction: column;
    text-align: center;
  }
  
  .resource-link i {
    margin-right: 0;
    margin-bottom: 1rem;
  }
}
</style>

<!--Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).-->