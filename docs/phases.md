![Social Impact Cycle for Hydrology Modeling](images/ToC.png)



<div class ="tab">
 <button class="tablinks" onclick="openPhase(event, 'Phase1')">Phase 1</button>
  <button class="tablinks" onclick="openPhase(event, 'Phase2')">Phase 2</button>
  <button class="tablinks" onclick="openPhase(event, 'Phase3')">Phase 3</button>
  <button class="tablinks" onclick="openPhase(event, 'Phase4')">Phase 4</button>
</div>

<div id="Phase1" class="tabcontent" style="display:block;">










<div id="Phase2" class="tabcontent">


</div>














<div id="Phase3" class="tabcontent">


</div>

<h3 id="Phase4" class="tabcontent">

<h2><strong>Phase IV: Expansion and Equity</strong><h2>

<h3><strong>How can we scale up?</strong></h3>

<p>In this phase, efforts are focused on scaling successful practices to new areas while ensuring equitable and inclusive water governance. Scaling Up involves replicating proven strategies in other countries or regions, drawing lessons from previous successes and challenges to refine implementation. This approach enhances the ability to sustain benefits across diverse contexts.</p>


<p>Inclusive Water Governance ensures that model benefits are accessible to all, emphasizing the importance of inviting and collaborating with stakeholders within the country. This inclusivity promotes long-term sustainability by fostering collective ownership and support.</p>


<p>Examples of these efforts include use cases from Costa Rica and Ecuador, where lessons learned from these experiences are applied to expand initiatives. By combining scaling strategies with inclusive governance, the phase aims to create a robust and adaptable framework for water management, benefiting a broader range of communities and stakeholders.
</p>





![Use Cases](phase2visuals/Use_Cases_CR_Ecuador.png)
Figure 12. Use Cases for Costa Rica and Ecuador

</div>



<script>
function openPhase(evt, phaseName) {
    // Hide all tab content
    let tabcontent = document.getElementsByClassName("tabcontent");
    for (let i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }

    // Remove "active" class from all buttons
    let tablinks = document.getElementsByClassName("tablinks");
    for (let i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }

    // Show the clicked tab content and add "active" class to button
    document.getElementById(phaseName).style.display = "block";
    evt.currentTarget.className += " active";
}

// Optional: Automatically open the first tab on page load
document.addEventListener("DOMContentLoaded", function() {
    document.querySelector(".tab .tablinks").click();
});
</script>

<style>
/* Style the tabs */
.tab {
  display: flex;
  margin-bottom: 20px;
}

/* Style the buttons */
.tablinks {
  background-color: #f1f1f1;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

.tablinks.active {
  background-color: #ccc;
}

/* Hide all tab content by default */
.tabcontent {
  display: none;
}
</style>


