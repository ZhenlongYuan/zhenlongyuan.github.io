# 🎯 Research Areas

<div class="research-visualization">
  <div class="keyword-cloud" id="keywordCloud">
    <!-- Keywords will be auto-generated -->
  </div>
</div>

<style>
.research-visualization {
  margin: 1.5em 0;
  text-align: center;
}

.keyword-cloud {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8em;
  justify-content: center;
  padding: 1em;
}

.keyword {
  display: inline-block;
  padding: 0.5em 1.2em;
  background: linear-gradient(135deg, #667eea, #764ba2);
  color: white;
  border-radius: 25px;
  font-weight: 500;
  transition: all 0.2s ease;
  cursor: default;
  box-shadow: 0 2px 8px rgba(102, 126, 234, 0.3);
}

.keyword[data-weight="5"] {
  font-size: 1.15em;
  padding: 0.6em 1.4em;
  background: linear-gradient(135deg, #9C27B0, #673AB7);
  box-shadow: 0 4px 12px rgba(156, 39, 176, 0.4);
}

.keyword[data-weight="4"] {
  font-size: 1.0em;
  padding: 0.55em 1.3em;
}

.keyword[data-weight="3"] {
  font-size: 0.9em;
  opacity: 0.95;
}

.keyword:hover {
  transform: translateY(-3px) scale(1.05);
  box-shadow: 0 6px 16px rgba(102, 126, 234, 0.4);
}
</style>

<script>
window.addEventListener('load', function() {
  const coreKeywords = [
    { keyword: '💻 Vision-Language Model', weight: 5 },
    { keyword: '🤖 Vision-Language Action', weight: 5 },
    { keyword: '🧠 Agentic Reinforcement Learning', weight: 5 },
    { keyword: '🦾 Embodied Agents', weight: 3 },
    { keyword: '🗺️ Spatial Intelligence', weight: 3 },
    { keyword: '🚀 Foundation Model', weight: 3 },
    { keyword: '🏥 AI for Science', weight: 3 },
    { keyword: '👁️ 3D Vision', weight: 3 },
    { keyword: '🛡️ Safety', weight: 3 }
  ];

  function generateKeywordCloud() {
    const keywordCloud = document.getElementById('keywordCloud');
    if (!keywordCloud) return;

    keywordCloud.innerHTML = coreKeywords.map(item =>
      `<span class="keyword" data-weight="${item.weight}">${item.keyword}</span>`
    ).join('');
  }

  generateKeywordCloud();
});
</script>
