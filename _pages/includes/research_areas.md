# 🎯 Research Interests

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
  font-size: 1.2em;
  padding: 0.6em 1.4em;
  background: linear-gradient(135deg, #9C27B0, #673AB7);
  box-shadow: 0 4px 12px rgba(156, 39, 176, 0.4);
}

.keyword[data-weight="4"] {
  font-size: 1.05em;
  padding: 0.55em 1.3em;
}

.keyword:hover {
  transform: translateY(-3px) scale(1.05);
  box-shadow: 0 6px 16px rgba(102, 126, 234, 0.4);
}
</style>

<script>
window.addEventListener('load', function() {
  const coreKeywords = [
    { keyword: '🤖 Vision-Language Model', weight: 5 },
    { keyword: '🧠 Agentic Reinforcement Learning', weight: 5 },
    { keyword: '📐 Spatial Intelligence', weight: 5 },
    { keyword: '🚀 Foundation Model', weight: 5 },
    { keyword: '🏥 AI for Science', weight: 5 },
    { keyword: '🦾 Embodied Agents', weight: 5 },
    { keyword: '⚡ Safety', weight: 5 },
    { keyword: '👁️ 3D Vision', weight: 5 }
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
