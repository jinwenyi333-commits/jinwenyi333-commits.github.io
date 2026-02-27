---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👨‍🎓 About Me
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Some Publications 
<div id="publications-container">
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
[Deep Residual Learning 1](https://link.com)
**Author**, etc.
- Description 1
  </div></div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
[Deep Residual Learning 2](https://link.com)
**Author**, etc.
- Description 2
  </div></div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
[Deep Residual Learning 2](https://link.com)
**Author**, etc.
- Description 3
  </div></div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
[Deep Residual Learning 2](https://link.com)
**Author**, etc.
- Description 4
  </div></div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
[Deep Residual Learning 2](https://link.com)
**Author**, etc.
- Description 5
  </div></div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
[Deep Residual Learning 2](https://link.com)
**Author**, etc.
- Description 6
  </div></div>


  </div>
<div id="pagination-controls" style="text-align: center; margin-top: 20px;">
  <button id="prev-page" class="btn btn--primary">上一页</button>
  <span id="page-info" style="margin: 0 15px;">第 1 页</span>
  <button id="next-page" class="btn btn--primary">下一页</button>
</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
    const itemsPerPage = 5; // 每页显示的行数
    const container = document.getElementById('publications-container');
    const items = Array.from(container.getElementsByClassName('paper-box'));
    const totalPages = Math.ceil(items.length / itemsPerPage);
    let currentPage = 1;

    function showPage(page) {
        const start = (page - 1) * itemsPerPage;
        const end = start + itemsPerPage;

        items.forEach((item, index) => {
            item.style.display = (index >= start && index < end) ? 'flex' : 'none';
        });

        document.getElementById('page-info').innerText = `第 ${page} / ${totalPages} 页`;
        document.getElementById('prev-page').disabled = (page === 1);
        document.getElementById('next-page').disabled = (page === totalPages);
        
        // 隐藏不需要的分页按钮（如果总数不到5个）
        if (totalPages <= 1) {
            document.getElementById('pagination-controls').style.display = 'none';
        }
    }

    document.getElementById('prev-page').addEventListener('click', () => {
        if (currentPage > 1) {
            currentPage--;
            showPage(currentPage);
            container.scrollIntoView({behavior: 'smooth'}); // 切换页码时自动回到顶部
        }
    });

    document.getElementById('next-page').addEventListener('click', () => {
        if (currentPage < totalPages) {
            currentPage++;
            showPage(currentPage);
            container.scrollIntoView({behavior: 'smooth'});
        }
    });

    showPage(currentPage);
});
</script>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
