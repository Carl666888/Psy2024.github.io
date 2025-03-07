# Psy2024.github.io
# 我的科研日志

## 📅 时间轴
- [2023年11月](2023-11.md)

## 📌 最新动态
- 2023-11-05 创建日志系统
## 🗓️ 日历视图
<script src="https://cdn.jsdelivr.net/npm/fullcalendar@6.1.8/index.global.min.js"></script>
<div id="calendar"></div>
<script>
document.addEventListener('DOMContentLoaded', function() {
  var calendarEl = document.getElementById('calendar');
  var calendar = new FullCalendar.Calendar(calendarEl, {
    initialView: 'dayGridMonth',
    events: [
      { title: '实验启动', start: '2023-11-05', url: '_posts/2023/11/2023-11-05.md' },
      { title: '论文阅读', start: '2023-11-06', url: '_posts/2023/11/2023-11-06.md' }
    ]
  });
  calendar.render();
});
</script>
