#### index.md
```markdown
---
layout: default
title: Home
---

# Welcome to ASSETS 2025 Participant Recruitment Workshop

Join us online Oct 20–26, 2025, to explore best practices and innovations in recruiting participants for accessibility research.

- [Call for Participation](/participate.html)
- [Schedule](/schedule.html)
- [Organizers](/organizers.html)


<!-- Countdown script -->
<script>
const deadline = new Date('Aug 8, 2025').getTime();
function updateCountdown() {
  const now = new Date().getTime();
  const diff = deadline - now;
  const days = Math.floor(diff / (1000 * 60 * 60 * 24));
  document.getElementById('countdown').innerText = days + ' days until SOI deadline';
}
setInterval(updateCountdown, 1000 * 60 * 60);
</script>
<p id="countdown"></p>
```  
