# 🎯 Research Interests

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
  border-radius: 25px;
  font-weight: 500;
  transition: all 0.2s ease;
  cursor: default;
}

/* Primary — large */
.keyword.primary {
  font-size: 1.2em;
  padding: 0.6em 1.5em;
  background: linear-gradient(135deg, #1565C0, #0D47A1);
  color: #fff;
  box-shadow: 0 4px 14px rgba(21, 101, 192, 0.35);
  font-weight: 600;
}
.keyword.primary:hover {
  transform: translateY(-3px) scale(1.05);
  box-shadow: 0 6px 18px rgba(21, 101, 192, 0.45);
}

/* Secondary — smaller */
.keyword.secondary {
  font-size: 0.9em;
  padding: 0.4em 1em;
  background: linear-gradient(135deg, #e8eaf6 0%, #c5cae9 100%);
  color: #283593;
  box-shadow: 0 2px 8px rgba(63, 81, 181, 0.15);
}
.keyword.secondary:hover {
  transform: translateY(-2px) scale(1.04);
  box-shadow: 0 4px 12px rgba(63, 81, 181, 0.25);
}
</style>

<div class="research-visualization">
  <div class="keyword-cloud" id="keywordCloud"></div>
</div>

<script>
window.addEventListener('load', function() {
  const keywords = [
    { text: '🤖 Vision-Language Model', primary: true },
    { text: '🧠 Agentic Reinforcement Learning', primary: true },
    { text: '🗺️ Spatial Intelligence', primary: true },
    { text: '🚀 Foundation Model', secondary: true },
    { text: '🏥 AI for Science', secondary: true },
    { text: '🦾 Embodied Agents', secondary: true },
    { text: '👁️ 3D Vision', secondary: true },
    { text: '🛡️ Safety', secondary: true }
  ];

  const cloud = document.getElementById('keywordCloud');
  if (!cloud) return;

  cloud.innerHTML = keywords.map(k =>
    `<span class="keyword ${k.primary ? 'primary' : 'secondary'}">${k.text}</span>`
  ).join('');
});
</script>