---
published: true
permalink: /data-model/
layout: visualization
filename: data-model.md
title: Data Model and Standards
page: data-model
---

<script>
  https://fiscal.treasury.gov/data-transparency/GSDM-current.html;
</script>

# Governmentwide Spending Data Model

The Governmentwide Spending Data Model (GSDM), formerly the DATA Act Information Model Schema (DAIMS), gives an overall view of the hundreds of distinct data elements used to tell the story of how federal dollars are spent. It includes artifacts that provide technical guidance for federal agencies about what data to report to Treasury including the authoritative sources of the data elements and the submission format. The GSDM also provides clarity on how the public can better understand the inherent complexity of the data. More information can be found on the Fiscal Service [GSDM](https://fiscal.treasury.gov/data-transparency/GSDM-current.html) website.

In the process to develop and mature this data model, initial collaboration with internal and external stakeholders began with a series of white papers and public feedback to gain consensus on the standardization of key spending data elements. 

The elements listed below represent the original consensus the federal community reached during the original DATA Act implementation. Since then, the community continues to iterate on these elements to improve standardization and overall clarity. Additional data elements will continue to be added as well, to continue improving transparency reporting. For the current data model element list visit the [GSDM](https://fiscal.treasury.gov/data-transparency/GSDM-current.html) website described above.
#### Awardee and Recipient Entity Information

This list includes information about recipients and awardees of federal funds. Please note that these elements will be standardized across the different types of awards (grants, contracts, etc.).

<table class='table-bordered'>
  <thead>
    <tr>
      <th scope="col">Data Element Name</th>
      <th scope="col">Legislation</th>
      <th scope="col">Provide Feedback</th>
    </tr>
  </thead>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/unique-id-business-name/" title="Unique Identifier and Legal Entity Name whitepaper">Awardee/Recipient Legal Entity Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/45" title="feedback for legal Entity name">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/unique-id-business-name/" title="Unique Identifier and Legal Entity Name whitepaper">Awardee/Recipient Unique Identifier</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/45" title="feedback for legal Entity identifier number">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/unique-id-business-name/" title="Unique Identifier and Legal Entity Name whitepaper">Ultimate Parent Unique Identifier</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/45" title="feedback for ultimate parent unique identifier">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/unique-id-business-name/" title="Unique Identifier and Legal Entity Name whitepaper">Ultimate Parent Legal Entity Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/45" title="feedback for ultimate parent legal Entity name">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/entity-address/" title="entity address whitepaper">Legal Entity Address</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/79" title="feedback for Legal Entity Address">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/entity-address/" title="entity address whitepaper">Legal Entity Congressional District</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/79" title="feedback for Legal Entity Address">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/entity-address/" title="entity address whitepaper">Legal Entity Country Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/79" title="feedback for Legal Entity Address">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/entity-address/" title="entity address whitepaper">Legal Entity Country Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/79" title="feedback for Legal Entity Country Name">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/highlycompensatedofficers/" title="Highly Compensated Officers whitepaper">Highly Compensated Officer Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/14" title="feedback for Highly Compensated Officer Name">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/highlycompensatedofficers/" title="Highly Compensated Officers whitepaper">Highly Compensated Officer Total Compensation</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/14" title="feedback for Highly Compensated Officer Total Compensation">feedback period closed</a></td>
  </tr>
</table>


#### Award Amount Information

This list includes elements used to describe the amount of a certain award.

<table class='table-bordered'>
  <thead>
    <tr>
      <th scope="col">Data Element Name</th>
      <th scope="col">Legislation</th>
      <th scope="col">Provide Feedback</th>
    </tr>
  </thead>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/amount/" title="Amounts whitepaper">Amount of Award*</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/76" title="feedback for Award Amount Information">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/amount/" title="Amounts whitepaper">Non-Federal Funding Amount</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/76" title="feedback for Award Amount Information">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/amount/" title="Amounts whitepaper">Federal Action Obligation*</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/76" title="feedback for Award Amount Information">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/amount/" title="Amounts whitepaper">Current Total Value of Award</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/76" title="feedback for Award Amount Information">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/amount/" title="Amounts whitepaper">Potential Total Value of Award</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/76" title="feedback for Award Amount Information">feedback period closed</a></td>
  </tr>
</table>


#### Award Characteristic Information

These elements describe the different characteristics each award possesses – for example, its transaction code, its Award Identification (ID) Number, and so on.

<table class='table-bordered'>
  <thead>
    <tr>
      <th scope="col">Data Element Name</th>
      <th scope="col">Legislation</th>
      <th scope="col">Provide Feedback</th>
    </tr>
  </thead>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/types/" title="Type of Transaction Code whitepaper">Award Type*</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/73" title="feedback Type of Transaction Code">feedback period closed</a></td>
  </tr>
    <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/naics/" title="North American Industrial Classification System whitepaper">North American Industrial Classification System (NAICS) Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/13" title="feedback for North American Industrial Classification System Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/naics/" title="North American Industrial Classification System whitepaper">North American Industrial Classification System (NAICS) Description</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/13" title="feedback for North American Industrial Classification System Description">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/cfdaprogramnumber-title/" title="CFDA Program Number_Title whitepaper">Catalog of Federal Domestic Assistance (CFDA) Number</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/67" title="feedback for Catalogue of Federal Domestic Assistance and Title">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/cfdaprogramnumber-title/" title="CFDA Program Number_Title whitepaper">Catalog of Federal Domestic Assistance (CFDA) Title</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/67" title="feedback for Catalogue of Federal Domestic Assistance and Title">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/approp-agency-tas/" title="Treasury Account Symbol, Agency, and Appropriations Fund whitepaper">Treasury Account Symbol (excluding Sub-Account)</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/32" title="feedback">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/award-id-description/" title="Award Identification (ID) Number and Description whitepaper">Award Description</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/78" title="feedback for Award Identification (ID) Number and Description">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/award-id-description/" title="Award Identification (ID) Number and Description whitepaper">Award Modification / Amendment Number</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/78" title="feedback for Award Identification (ID) Number and Description">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/award-id-description/" title="Award Identification (ID) Number and Description whitepaper">Parent Award Identification (ID) Number</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/78" title="feedback for Award Identification (ID) Number and Description">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/period-of-performance/" title="Period of Performance whitepaper">Action Date</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/71" title="feedback Action Date, Period of Performance, and Ordering Period End Date">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/period-of-performance/" title="Period of Performance whitepaper">Period of Performance Start Date</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/71" title="feedback Action Date, Period of Performance, and Ordering Period End Date">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/period-of-performance/" title="Period of Performance whitepaper">Period of Performance Current End Date</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/71" title="feedback Action Date, Period of Performance, and Ordering Period End Date">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/period-of-performance/" title="Period of Performance whitepaper">Period of Performance Potential End Date</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/71" title="feedback Action Date, Period of Performance, and Ordering Period End Date">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/period-of-performance/" title="Period of Performance whitepaper">Ordering Period End Date</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/71" title="feedback Action Date, Period of Performance, and Ordering Period End Date">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/place-of-performance/" title="Place of Performance whitepaper">Primary Place of Performance Address</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/72" title="feedback Primary Place of Performance">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/place-of-performance/" title="Place of Performance whitepaper">Primary Place of Performance Congressional District</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/72" title="feedback Primary Place of Performance">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/place-of-performance/" title="Place of Performance whitepaper">Primary Place of Performance Country Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/72" title="feedback Primary Place of Performance">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/place-of-performance/" title="Place of Performance whitepaper">Primary Place of Performance Country Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/72" title="feedback Primary Place of Performance">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/award-id-description/" title="Award Identification (ID) Number and Description whitepaper">Award Identification (ID) Number</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/78" title="feedback for Award Identification (ID) Number and Description">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/types/" title="Type of Transaction Code whitepaper">Record Type</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/73" title="feedback Type of Transaction Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/types/" title="Type of Transaction Code whitepaper">Action Type*</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/73" title="feedback Type of Transaction Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/business-types/" title="Business Type whitepaper">Business Types*</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/77" title="feedback Business Type">feedback period closed</a></td>
  </tr>
</table>


#### Funding Entity Information

These data elements describe characteristics of the entity that provided funding for an award.

<table class='table-bordered'>
  <thead>
    <tr>
      <th scope="col">Data Element Name</th>
      <th scope="col">Legislation</th>
      <th scope="col">Provide Feedback</th>
    </tr>
  </thead>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/fundingagency/" title="Funding Agency Name whitepaper">Funding Agency Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/68" title="leave feedback for Funding Agency Name and Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/fundingagency/" title="Funding Agency Name whitepaper">Funding Agency Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/68" title="leave feedback for Funding Agency Name and Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Funding Sub Tier Agency Name whitepaper">Funding Sub Tier Agency Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/70" title="Funding Sub Tier Agency Name/Code And Funding Office Name/Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Funding Sub Tier Agency Name whitepaper">Funding Sub Tier Agency Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/70" title="Funding Sub Tier Agency Name/Code And Funding Office Name/Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Funding Sub Tier Agency Name whitepaper">Funding Office Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/70" title="Funding Sub Tier Agency Name/Code And Funding Office Name/Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Funding Sub Tier Agency Name whitepaper">Funding Office Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/70" title="Funding Sub Tier Agency Name/Code And Funding Office Name/Code">feedback period closed</a></td>
  </tr>
</table>


#### Awarding Entity Information

Elements on this list describe awarding entities – those that presented the awardee with the funding.

<table class='table-bordered'>
  <thead>
    <tr>
      <th scope="col">Data Element Name</th>
      <th scope="col">Legislation</th>
      <th scope="col">Provide Feedback</th>
    </tr>
  </thead>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/fundingagency/" title="Treasury Account Symbol, Agency, and Appropriations Fund whitepaper">Awarding Agency Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/32" title="feedback for Awarding Agency Name">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/fundingagency/" title="Treasury Account Symbol, Agency, and Appropriations Fund whitepaper">Awarding Agency Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/32" title="feedback for Awarding Agency Code">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Awarding Sub Tier Agency and Office whitepaper">Awarding Sub Tier Agency Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/75" title="leave feedback Awarding Sub Tier Agency">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Awarding Sub Tier Agency and Office whitepaper">Awarding Sub Tier Agency Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/75" title="leave feedback Awarding Sub Tier Agency">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Awarding Sub Tier Agency and Office whitepaper">Awarding Office Name</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/75" title="leave feedback Awarding Sub Tier Agency">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/sub-tier-agency/" title="Awarding Sub Tier Agency and Office whitepaper">Awarding Office Code</a></td>
    <td>FFATA</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/75" title="leave feedback Awarding Sub Tier Agency">feedback period closed</a></td>
  </tr>
</table>


#### Account Level Information

This list features elements that describe the accounts from which the awards are funded.

<table class='table-bordered'>
  <thead>
    <tr>
      <th scope="col">Data Element Name</th>
      <th scope="col">Legislation</th>
      <th scope="col">Provide Feedback</th>
    </tr>
  </thead>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/objectclass/" title="Object Class whitepaper">Object Class</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/19" title="feedback for Object Class">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/approp-agency-tas/" title="Treasury Account Symbol, Agency, and Appropriations Fund whitepaper">Appropriations Account</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/32" title="feedback for Appropriations Account">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/ba-appropriated-other-resources/" title="Budget Authority Amount and Other Budgetary Resources whitepaper">Budget Authority Appropriated</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/31" title="feedback for Budget Authority Appropriated">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/obligation/" title="Obligation whitepaper">Obligation</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/20" title="feedback for Obligation">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/unobligated-balance/" title="Unobligated balance whitepaper">Unobligated Balance</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/51" title="feedback for Unobligated balance">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/ba-appropriated-other-resources/" title="Budget Authority Amount and Other Budgetary Resources whitepaper">Other Budgetary Resources</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/31" title="feedback for Other Budgetary Resources">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/programactivity/" title="Program Activity whitepaper">Program Activity</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/21" title="feedback for Program Activity">feedback period closed</a></td>
  </tr>
  <tr>
    <td><a href="{{ site.baseurl }}/whitepapers/outlay/" title="Outlay whitepaper">Outlay</a></td>
    <td>DATA Act</td>
    <td><a href="https://github.com/fedspendingtransparency/fedspendingtransparency.github.io/issues/30" title="feedback for Outlay">feedback period closed</a></td>
  </tr>
</table>

\* An asterisk (*) next to a data element name indicates that the name for that data element has changed since it was first posted here in December 2014.  All final data element names and definitions are posted [here](https://max.gov/datastandards).
