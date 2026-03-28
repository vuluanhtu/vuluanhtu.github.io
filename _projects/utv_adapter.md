---
layout: page
title: Modular Attachment Adapter for Utility Terrain Vehicle
description: Senior capstone design project - Quick-connect implement system for utility vehicles
img: assets/img/projects/utv_adapter/final_presentation_poster.jpg
importance: 2
category: design
toc:
  sidebar: left
images:
  photoswipe: true
---

> ##### PROJECT HIGHLIGHTS
>
> **45+** component assembly • **$1,000** budget • **115-page** technical report
>
> 📅 Jan 2020 - Dec 2020 | 🎓 Senior Capstone | 🏛️ Purdue University Fort Wayne | 🏢 Sponsor: American Landmaster
{: .block-tip }

## Project Overview
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

**Duration:** January 2020 - December 2020  
**Type:** Senior Capstone Design Project  
**Sponsor:** American Landmaster  
**Budget:** $1,000  
**Team:** Multi-disciplinary student engineering team

Developed a modular attachment adapter system for utility terrain vehicles (UTVs), enabling quick and easy attachment of various implements. This project combined mechanical design, structural analysis, and practical fabrication constraints to deliver a functional prototype within budget.

---

## Design Challenge
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

American Landmaster required a modular lift mechanism that would allow their UTV customers to quickly swap between different attachments (plows, buckets, forks, etc.) without tools. The system needed to be:

> **🎯 Cost-effective** — Manufacturable within a $1,000 budget
{: .block-tip }

> **🔒 Reliable** — Safe operation under various load conditions
{: .block-tip }

> **🔧 User-friendly** — Quick-connect mechanism for field use
{: .block-tip }

> **🔗 Universal** — Compatible with standard implement interfaces
{: .block-tip }

---

## Technical Solution
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Concept Selection
{: .mt-4 .mb-3 .font-weight-bold }

Multiple design concepts were evaluated using a weighted decision matrix to identify the best kinematic mechanism for the lift system. Criteria included manufacturability, cost, reliability, and ease of use.

<div class="pswp-gallery" id="gallery-concept">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/weighting_matrix_for_kinematic_mechanism_system.jpg' | relative_url }}" data-pswp-width="1564" data-pswp-height="1196" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/weighting_matrix_for_kinematic_mechanism_system.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Weighting Matrix for Kinematic Mechanism System" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/combined_score_of_weighting_matrix_for_kinematic_mechanism_system_to_select_best_concept.jpg' | relative_url }}" data-pswp-width="1410" data-pswp-height="290" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/combined_score_of_weighting_matrix_for_kinematic_mechanism_system_to_select_best_concept.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Combined Score for Concept Selection" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Weighted decision matrix (left) and combined scores identifying the best kinematic concept (right)
</div>

### Mechanical Design
{: .mt-4 .mb-3 .font-weight-bold }
Designed a complete sheet metal and mechanical assembly system consisting of 45+ components, integrating both custom-fabricated and off-the-shelf parts.

**Key Components:**

- Custom sheet metal frame and brackets
- Linear actuator for powered lifting
- Spring-assisted quick-connect mechanism
- Pulley and cable system for load distribution
- Bearing-mounted pivot points for smooth operation

**CAD Development:**

- Created complete assembly in SolidWorks
- Generated detailed fabrication drawings with GD&T
- Developed complete BOM with cost breakdown
- Part sourcing and supplier coordination

### Analysis & Validation
{: .mt-4 .mb-3 .font-weight-bold }
Comprehensive engineering analysis ensured safe and reliable operation:

**Kinematic Analysis:**

A four-bar linkage was used as the basis for the lift mechanism. MATLAB and SolidWorks simulations verified motion range and interference clearance.

<div class="pswp-gallery" id="gallery-kinematics">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/four_bar_linkage_illustration_for_kinematic_analysis.jpg' | relative_url }}" data-pswp-width="720" data-pswp-height="420" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/four_bar_linkage_illustration_for_kinematic_analysis.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Four Bar Linkage Illustration" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/kinematic_analysis_in_MATLAB_Solidworks.jpg' | relative_url }}" data-pswp-width="720" data-pswp-height="514" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/kinematic_analysis_in_MATLAB_Solidworks.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Kinematic Analysis in MATLAB and SolidWorks" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Four-bar linkage schematic (left) and kinematic simulation output comparing MATLAB vs SolidWorks results (right)
</div>

**Dynamic Analysis:**

<div class="pswp-gallery" id="gallery-dynamics">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/force_analysis_MATLAB_Solidworks.jpg' | relative_url }}" data-pswp-width="975" data-pswp-height="1123" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/force_analysis_MATLAB_Solidworks.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Force Analysis MATLAB vs SolidWorks" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/drive_torque_analysis_MATLAB_Solidworks.jpg' | relative_url }}" data-pswp-width="1809" data-pswp-height="1008" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/drive_torque_analysis_MATLAB_Solidworks.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Drive Torque Analysis MATLAB vs SolidWorks" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Joint force analysis (left) and drive torque analysis (right) cross-validated between MATLAB and SolidWorks
</div>

**Structural FEA:**

<div class="pswp-gallery" id="gallery-fea">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/FEA_of_top_plate.jpg' | relative_url }}" data-pswp-width="1872" data-pswp-height="1181" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/FEA_of_top_plate.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="FEA of Top Plate" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/FEA_of_bolt.jpg' | relative_url }}" data-pswp-width="1933" data-pswp-height="868" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/FEA_of_bolt.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="FEA of Bolt" />
      </a>
    </div>
  </div>
  <div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/FBD_ground_link_for_stress_hand_calculation.jpg' | relative_url }}" data-pswp-width="252" data-pswp-height="426" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/FBD_ground_link_for_stress_hand_calculation.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="FBD Ground Link for Stress Hand Calculation" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/stress_hand_calculation_match_FEA.jpg' | relative_url }}" data-pswp-width="1028" data-pswp-height="414" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/stress_hand_calculation_match_FEA.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Stress Hand Calculation Matching FEA" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/FEA_ground_link_match_hand_calculation.jpg' | relative_url }}" data-pswp-width="368" data-pswp-height="387" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/FEA_ground_link_match_hand_calculation.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="FEA Ground Link Matching Hand Calculation" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  FEA of top plate and bolt connections (top row) • FBD, hand calculation, and FEA result of ground link — cross-validated to confirm analysis accuracy (bottom row)
</div>

**Testing:**

- Physical prototype testing
- Load testing to verify capacity
- Reliability testing under field conditions
- Test data summarized in 115-page technical report

---

## Fabrication & Manufacturing
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Technical Drawings
{: .mt-4 .mb-3 .font-weight-bold }

<div class="pswp-gallery" id="gallery-drawings">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/Final_assembly_drawing_non_exploded_no_BOM.jpg' | relative_url }}" data-pswp-width="755" data-pswp-height="1045" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/Final_assembly_drawing_non_exploded_no_BOM.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Final Assembly Drawing" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/utv_final_assembly_drawing_exploded.jpg' | relative_url }}" data-pswp-width="1574" data-pswp-height="1139" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/utv_final_assembly_drawing_exploded.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="UTV Final Assembly Drawing Exploded View" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Final assembly drawing (left) and exploded view with complete BOM (right)
</div>

### Bill of Materials
{: .mt-4 .mb-3 .font-weight-bold }

<div class="pswp-gallery" id="gallery-bom">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/final_bom_with_cost.jpg' | relative_url }}" data-pswp-width="1073" data-pswp-height="1165" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/final_bom_with_cost.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Final BOM with Cost" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/final_bom_with_cost_continued.jpg' | relative_url }}" data-pswp-width="1068" data-pswp-height="1092" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/final_bom_with_cost_continued.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Final BOM with Cost (continued)" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Complete bill of materials with supplier pricing, staying within the $1,000 budget
</div>

---

## Prototyping & Testing
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

All components were fabricated and assembled for functional prototype testing including load capacity verification and field condition reliability testing.

<div class="pswp-gallery" id="gallery-prototype">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/prototype_top_and_prototype_installed_on_utv_with_bucket_attachment_bottom.jpg' | relative_url }}" data-pswp-width="1051" data-pswp-height="1164" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/prototype_top_and_prototype_installed_on_utv_with_bucket_attachment_bottom.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Prototype and Installation on UTV" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/built_prototype_tested_on_utv.jpg' | relative_url }}" data-pswp-width="2180" data-pswp-height="886" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/built_prototype_tested_on_utv.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Built Prototype Tested on UTV" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Assembled prototype with bucket attachment installed on UTV (left) and field testing of the functional prototype (right)
</div>

> **Testing Results**
>
> Physical prototype testing confirmed design validity with load capacity verification and field condition reliability testing, all documented in the **115-page technical report**.
{: .block-tip }

---

## Project Outcomes
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

**Deliverables:**

- Functional prototype demonstrating proof-of-concept
- 115-page technical report documenting design process
- Complete CAD assembly and fabrication drawings
- BOM with cost analysis
- Test data and performance validation

### Final Presentation Poster
{: .mt-4 .mb-3 .font-weight-bold }

<div class="pswp-gallery" id="gallery-poster">
  <div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/utv_adapter/final_presentation_poster.jpg' | relative_url }}" data-pswp-width="5376" data-pswp-height="3840" target="_blank">
        <img src="{{ '/assets/img/projects/utv_adapter/final_presentation_poster.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Final Presentation Poster" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Senior capstone design project final presentation poster summarizing the complete design process
</div>

**Client Presentation:**

- Presented design to American Landmaster engineering team
- Received feedback for potential production improvements
- Demonstrated cost-effective approach to modular implement systems

---

## Technical Skills Demonstrated
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

- **Design for Manufacturing** - Sheet metal and weldment design
- **CAD/BOM Management** - Complex assembly with 45+ components
- **GD&T** - Proper dimensioning and tolerancing
- **Mechanism Design** - Quick-connect and lift systems
- **Analysis** - Kinematics, dynamics, and structural validation
- **Project Management** - Budget control, team coordination
- **Technical Communication** - 115-page report, client presentations
- **Procurement** - Supplier selection and cost optimization

---

## Engineering Value
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

This project demonstrates practical engineering skills critical for product development:

- Working within budget constraints
- Balancing performance and manufacturability
- Integrating purchased and custom components
- Collaborating with stakeholders (sponsor, team, manufacturers)
- Delivering complete documentation for production

The modular adapter concept addresses a real market need for versatile utility vehicles, showing how thoughtful mechanical design can add significant value to existing products.
