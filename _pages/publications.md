---
layout: default
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<div class="publications-page">
  <h1>Publications</h1>
  
  <div class="publications-header">
    <p>You can also find my articles on my <a href="https://scholar.google.com/citations?user=bqyCK7cAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar-square ai-2x" style="font-size: 0.95em;"> <b>Google Scholar</b></i></a></p>
  </div>

  <div class="publications-filters">
    <h3>Filter by Type:</h3>
    <div class="filter-buttons">
      <button class="filter-btn active" data-filter="all">All Publications</button>
      <button class="filter-btn" data-filter="conference">Conference</button>
      <button class="filter-btn" data-filter="journal">Journal</button>
      <button class="filter-btn" data-filter="workshop">Workshop</button>
    </div>
  </div>

  <div class="publications-list">
    <h3>(2015 Onwards)</h3>
    
    {% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
    {% for post in sorted_pubs %}
      {% assign pub_type = 'conference' %}
      {% if post.venue contains 'Journal' or post.venue contains 'ACM' or post.venue contains 'IEEE Transactions' or post.venue contains 'Elsevier' %}
        {% assign pub_type = 'journal' %}
      {% elsif post.venue contains 'Workshop' or post.venue contains 'WIP' %}
        {% assign pub_type = 'workshop' %}
      {% endif %}
      
      <div class="publication-item" data-type="{{ pub_type }}">
        <div class="pub-number">{{ forloop.index }}</div>
        <div class="pub-content">
          <div class="pub-authors">{{ post.authors }}</div>
          <div class="pub-title">"{{ post.title }}"</div>
          <div class="pub-venue">{{ post.venue }}</div>
          {% if post.paperurl %}
            <div class="pub-links">
              <a href="{{ post.paperurl }}" target="_blank" class="pub-link">
                <i class="fas fa-file-pdf"></i> Paper
              </a>
              {% if post.github %}
                <a href="{{ post.github }}" target="_blank" class="pub-link">
                  <i class="fab fa-github"></i> Code
                </a>
              {% endif %}
              {% if post.slides %}
                <a href="{{ post.slides }}" target="_blank" class="pub-link">
                  <i class="fas fa-file-powerpoint"></i> Slides
                </a>
              {% endif %}
              {% if post.video %}
                <a href="{{ post.video }}" target="_blank" class="pub-link">
                  <i class="fab fa-youtube"></i> Video
                </a>
              {% endif %}
            </div>
          {% endif %}
        </div>
      </div>
    {% endfor %}
  </div>
</div>

<style>
.publications-page {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 1rem;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

.publications-page h1 {
  color: #2c3e50;
  border-bottom: 3px solid #3498db;
  padding-bottom: 0.5rem;
  margin-bottom: 2rem;
  font-size: 2.5rem;
}

.publications-header {
  margin-bottom: 2rem;
  text-align: center;
}

.publications-header p {
  font-size: 1.1rem;
  color: #555;
}

.publications-filters {
  margin-bottom: 2rem;
  padding: 1.5rem;
  background-color: #f8f9fa;
  border-radius: 8px;
  border-left: 4px solid #3498db;
}

.publications-filters h3 {
  margin-bottom: 1rem;
  color: #2c3e50;
  font-size: 1.3rem;
}

.filter-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.filter-btn {
  padding: 0.5rem 1rem;
  border: 2px solid #3498db;
  background-color: white;
  color: #3498db;
  border-radius: 20px;
  cursor: pointer;
  transition: all 0.3s ease;
  font-weight: 500;
}

.filter-btn:hover {
  background-color: #3498db;
  color: white;
}

.filter-btn.active {
  background-color: #3498db;
  color: white;
}

.publications-list h3 {
  color: #2c3e50;
  margin-bottom: 1.5rem;
  font-size: 1.4rem;
  font-weight: 600;
}

.publication-item {
  display: flex;
  margin-bottom: 1.5rem;
  padding: 1.5rem;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  border-left: 4px solid #e74c3c;
  transition: all 0.3s ease;
}

.publication-item:hover {
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
  transform: translateY(-2px);
}



.pub-number {
  flex-shrink: 0;
  width: 40px;
  height: 40px;
  background-color: #e74c3c;
  color: white;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  margin-right: 1.5rem;
  font-size: 0.9rem;
}

.pub-content {
  flex: 1;
}

.pub-authors {
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 0.5rem;
  line-height: 1.4;
}

.pub-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.5rem;
  line-height: 1.4;
}

.pub-venue {
  font-size: 1rem;
  color: #e74c3c;
  font-weight: 500;
  margin-bottom: 0.8rem;
}

.pub-links {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.pub-link {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  padding: 0.3rem 0.8rem;
  background-color: #f8f9fa;
  color: #3498db;
  text-decoration: none;
  border-radius: 4px;
  font-size: 0.9rem;
  transition: all 0.3s ease;
  border: 1px solid #e9ecef;
}

.pub-link:hover {
  background-color: #3498db;
  color: white;
  text-decoration: none;
}

.pub-link i {
  font-size: 0.8rem;
}

/* Mobile responsiveness */
@media (max-width: 768px) {
  .publications-page {
    padding: 1rem 0.5rem;
  }
  
  .publications-page h1 {
    font-size: 2rem;
  }
  
  .filter-buttons {
    justify-content: center;
  }
  
  .filter-btn {
    font-size: 0.9rem;
    padding: 0.4rem 0.8rem;
  }
  
  .publication-item {
    flex-direction: column;
    padding: 1rem;
  }
  
  .pub-number {
    align-self: flex-start;
    margin-bottom: 1rem;
    margin-right: 0;
  }
  
  .pub-links {
    justify-content: flex-start;
  }
}

@media (max-width: 480px) {
  .publications-page h1 {
    font-size: 1.8rem;
  }
  
  .pub-title {
    font-size: 1rem;
  }
  
  .pub-venue {
    font-size: 0.9rem;
  }
  
  .pub-links {
    flex-direction: column;
    gap: 0.5rem;
  }
  
  .pub-link {
    justify-content: center;
  }
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const filterButtons = document.querySelectorAll('.filter-btn');
  const publicationItems = document.querySelectorAll('.publication-item');
  
  filterButtons.forEach(button => {
    button.addEventListener('click', function() {
      // Remove active class from all buttons
      filterButtons.forEach(btn => btn.classList.remove('active'));
      // Add active class to clicked button
      this.classList.add('active');
      
      const filter = this.getAttribute('data-filter');
      
      publicationItems.forEach(item => {
        if (filter === 'all' || item.getAttribute('data-type') === filter) {
          item.style.display = 'flex';
        } else {
          item.style.display = 'none';
        }
      });
    });
  });
});
</script>
