# 🏆 Honors and Awards

<style>
#honors-awards details {
  margin-bottom: 1em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border: 1px solid #e8e8e8;
  transition: box-shadow 0.3s;
}
#honors-awards details:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#honors-awards details[open] {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}

#honors-awards summary {
  padding: 0.9em 1.2em;
  cursor: pointer;
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  background: linear-gradient(135deg, #f8f9fa 0%, #eef1f5 100%);
  user-select: none;
  display: flex;
  align-items: center;
  gap: 0.5em;
  list-style: none;
  transition: background 0.2s;
}
#honors-awards summary::-webkit-details-marker { display: none; }
#honors-awards summary::before {
  content: "▶";
  font-size: 0.7em;
  color: #2196F3;
  transition: transform 0.25s;
  display: inline-block;
}
#honors-awards details[open] > summary::before {
  transform: rotate(90deg);
}
#honors-awards summary:hover {
  background: linear-gradient(135deg, #eef1f5 0%, #e3e8ef 100%);
}

#honors-awards .badge-count {
  font-size: 0.75em;
  font-weight: 500;
  color: #fff;
  background: #2196F3;
  padding: 2px 9px;
  border-radius: 12px;
  margin-left: auto;
}

#honors-awards .award-list {
  list-style: none;
  padding: 0;
  margin: 0;
  counter-reset: award-counter;
}
#honors-awards .award-list > li {
  counter-increment: award-counter;
  padding: 1em 1.3em;
  border-bottom: 1px solid #f0f0f0;
  position: relative;
  transition: background 0.15s;
}
#honors-awards .award-list > li:last-child { border-bottom: none; }
#honors-awards .award-list > li:hover { background: #fafbfc; }
#honors-awards .award-list > li::before {
  content: "[" counter(award-counter) "]";
  font-weight: bold;
  color: #2196F3;
  margin-right: 0.5em;
  font-size: 0.95em;
}

#honors-awards .award-list > li > strong {
  font-size: 1.02em;
  color: #1a1a1a;
}

#honors-awards .award-list > li > ul {
  margin-top: 0.5em;
  margin-bottom: 0;
  padding-left: 1.5em;
  list-style-type: none;
}
#honors-awards .award-list > li > ul > li {
  margin-bottom: 0.3em;
  line-height: 1.6;
  color: #555;
  position: relative;
  padding-left: 0;
}
#honors-awards .award-list > li > ul > li::before {
  content: "▪ ";
  color: #2196F3;
  font-weight: bold;
  margin-right: 0.3em;
}

#honors-awards a {
  color: #2196F3;
  text-decoration: none;
  transition: all 0.2s;
  padding: 1px 4px;
  border-radius: 4px;
  display: inline;
}
#honors-awards a:hover {
  color: #1976D2;
  background: #e3f2fd;
}
#honors-awards .award-date {
  color: #666;
  font-style: italic;
  margin-left: 0.5em;
  font-size: 0.92em;
}
</style>

<div id="honors-awards">

<details open>
<summary>🥇 Conference & Academic Service <span class="badge-count">1</span></summary>
<ul class="award-list">

<li><strong>Conference Reviewers</strong>
  <ul>
    <li><strong>NeurIPS</strong>, <strong>ICML</strong>, <strong>ICLR</strong>, <strong>CVPR</strong>, <strong>ICCV</strong>, <strong>ECCV</strong>, <strong>AAAI</strong></li>
  </ul>
</li>

<li><strong>Journal Reviewers</strong>
  <ul>
    <li><strong>IJCV</strong>, <strong>TIP</strong>, <strong>TMM</strong>, <strong>TNNLS</strong>, <strong>TCSVT</strong>, <strong>PR</strong></li>
  </ul>
</li>

</ul>
</details>

</div>
