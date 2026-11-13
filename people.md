---
layout: page
title: People
subtitle: Meet the Sun Research Group
permalink: /people/
---

<!--
EDITING THIS PAGE
1. Replace the sample details below with your group members' information.
2. Upload photos to assets/img/people/ in your GitHub repository.
3. Replace a person's <div class="person-photo-placeholder">...</div> with
   the <img> line provided in the comment directly below it.
4. Copy an entire <article class="person">...</article> to add a person.
   Update the photo filename, alt text, name, role, education, and interests.
5. Delete unused sample cards or sections before publishing.
Photos are cropped to a consistent square; JPG or PNG files work well.
-->

<style>
.people-list .person {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  padding: 24px 0;
  border-bottom: 1px solid #e5e5e5;
}
.people-list .person-photo,
.people-list .person-photo-placeholder {
  width: 160px;
  height: 160px;
  flex: 0 0 160px;
  border-radius: 6px;
}
.people-list .person-photo { object-fit: cover; }
.people-list .person-photo-placeholder {
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f1f1f1;
  color: #666;
  font-size: 16px;
}
.people-list .person-details { flex: 1; min-width: 0; }
.people-list .person-details h3 { margin: 0 0 6px; }
.people-list .person-role { color: #666; margin: 0 0 12px; }
.people-list .person-details p { margin-bottom: 10px; }
.people-list .person-details ul { padding-left: 20px; }
@media (max-width: 575px) {
  .people-list .person { flex-direction: column; gap: 16px; }
  .people-list .person-photo,
  .people-list .person-photo-placeholder { flex-basis: auto; }
}
</style>

## Principal Investigator

<div class="people-list">
<article class="person">
  <img class="person-photo" src="{{ '/assets/img/people/rui-sun.png' | relative_url }}" alt="Rui Sun" width="160" height="160" loading="lazy">
  <div class="person-details">
    <h3>Rui Sun</h3>
    <p class="person-role">Thomas J. Barton Chair Professor</p>
    <p><strong>Education</strong></p>
    <ul>
      <li>Postdoc, [The University of Chicago]</li>
      <li>Ph.D., [Texas Tech University]</li>
      <li>B.S., [Shandong University]</li>
    </ul>
    <p><a href="mailto:ruisun@iastate.edu">Email</a></p>
  </div>
</article>
</div>

## Postdoctoral Researchers

<div class="people-list">
<!-- Copy this article to add another postdoctoral researcher. -->
<article class="person">
  <div class="person-photo-placeholder">Photo</div>
  <!-- Replace the placeholder above with this line after uploading the photo:
  <img class="person-photo" src="{{ '/assets/img/people/postdoc-name.jpg' | relative_url }}" alt="[Full name]" width="160" height="160" loading="lazy">
  -->
  <div class="person-details">
    <h3>[Full name]</h3>
    <p class="person-role">Postdoctoral Researcher</p>
    <p><strong>Education</strong></p>
    <ul>
      <li>Ph.D., [Field], [University], [Year]</li>
      <li>B.S., [Field], [University], [Year]</li>
    </ul>
    <p><strong>Research interests:</strong> [Add a short description.]</p>
    <p><strong>Joined:</strong> [Year]</p>
  </div>
</article>
</div>

## Graduate Students

<div class="people-list">
<!-- Copy this article to add another graduate student. -->
<article class="person">
  <div class="person-photo-placeholder">Photo</div>
  <!-- Replace the placeholder above with this line after uploading the photo:
  <img class="person-photo" src="{{ '/assets/img/people/student-name.jpg' | relative_url }}" alt="[Full name]" width="160" height="160" loading="lazy">
  -->
  <div class="person-details">
    <h3>[Full name]</h3>
    <p class="person-role">Graduate Student</p>
    <p><strong>Education</strong></p>
    <ul>
      <li>B.S., [Field], [University], [Year]</li>
    </ul>
    <p><strong>Research interests:</strong> [Add a short description.]</p>
    <p><strong>Joined:</strong> [Year]</p>
  </div>
</article>
</div>

<div class="people-list">
<!-- Copy this article to add another graduate student. -->
<article class="person">
  <div class="person-photo-placeholder">Photo</div>
  <!-- Replace the placeholder above with this line after uploading the photo:
  <img class="person-photo" src="{{ '/assets/img/people/student-name.jpg' | relative_url }}" alt="[Full name]" width="160" height="160" loading="lazy">
  -->
  <div class="person-details">
    <h3>[Full name]</h3>
    <p class="person-role">Graduate Student</p>
    <p><strong>Education</strong></p>
    <ul>
      <li>B.S., [Field], [University], [Year]</li>
    </ul>
    <p><strong>Research interests:</strong> [Add a short description.]</p>
    <p><strong>Joined:</strong> [Year]</p>
  </div>
</article>
</div>
