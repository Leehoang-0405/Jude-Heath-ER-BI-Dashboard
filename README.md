# Emergency Department Operational Performance & Patient Experience Analytics

## 1. Executive Summary
**The Business Problem:** St. Jude’s Health System faced a critical misalignment between Emergency Department staffing and patient demand, resulting in an average satisfaction score of 4.99 out of 10.

**The Failing Decision:** Hospital leadership was utilizing static staffing rosters that failed to account for predictable surge patterns, leading to an average wait time of 35.3 minutes across 9,216 annual visits.

**Scale of Impact:** Operational bottlenecks in General Practice and Orthopedics referrals, combined with poor satisfaction among the core 20 to 39 year old demographic, put community trust and institutional performance targets at risk.

**The Outcome:** This project delivered a three tier Power BI reporting suite that identifies high density arrival windows. The implementation provides a roadmap to reduce wait times by 15 percent and increase bed turnover by 20 percent through targeted specialist protocols.

## 2. Business Problem
**The Decision Framework:** The organization was repeatedly making staffing and resource allocation decisions based on traditional business hours rather than actual clinical demand cycles.

**Flawed Logic:** The previous operational model assumed a uniform distribution of patients throughout the week. This logic was flawed because it ignored concentrated spikes on Mondays (1,377 patients) and Saturdays (1,322 patients), as well as daily surges at 11:00, 13:00, 19:00, and 23:00.

**Operational Failure:** Without data driven visibility, the ER experienced moderate delays and below target satisfaction. Leadership could not distinguish between general volume pressure and specific departmental bottlenecks in General Practice and Orthopedics, leading to inefficient bed utilization and exit blocks.

## 3. Methodology
The project utilized a structured analytical approach to transform raw clinical data into executive insights:
* **Data Engineering:** Processed 9,216 patient records in Power Query to normalize demographics and extract temporal features from admission timestamps.
* **Tiered Architecture:** Developed a three page Power BI solution tailored to specific stakeholder needs:
    * **Consolidated View:** High level KPIs for C-Suite oversight of wait times and satisfaction.
    * **Monthly Operational View:** A temporal demand heatmap for Nurse Unit Managers to optimize rosters.
    * **Patient Details:** A granular drill through interface for Quality Assurance root cause analysis.
* **Metric Development:** Engineered DAX measures for Admission Rate percentages and demographic specific satisfaction benchmarks.

## 4. Demonstration of Skills and Capabilities
**Temporal Demand Profiling:** I identified that ER demand is not random but follows a predictable cycle. By mapping 9,216 visits, I isolated Monday as the busiest day and identified four specific peak hours. This proves the capability to provide HR with the exact timestamps required for roster optimization.

**Clinical Flow Optimization:**
I quantified the pressure on specialist departments by identifying that General Practice and Orthopedics receive 65 percent of all referrals. This demonstrates the ability to locate specific systemic bottlenecks that contribute to wait times.

**Demographic Segmentation:**
I isolated the 20 to 39 year old cohort (2,388 patients) as the primary driver of visits. By cross referencing this with an average satisfaction score of 4.99, I demonstrated the capability to identify high risk service gaps in the largest customer segment.



## 5. Results & Business Recommendations
**Finding 1: Staffing Misalignment**
* **Result:** Predictable spikes at 11:00, 13:00, 19:00, and 23:00 are currently underserved.
* **Recommendation:** Align rosters to these peak windows to reduce average wait times from 35.3 minutes to under 30 minutes.

**Finding 2: Specialist Transition Blocks**
* **Result:** 2,835 patients require referrals, with the majority directed to General Practice and Orthopedics.
* **Recommendation:** Establish priority consultation protocols to achieve a 20 percent increase in bed turnover rate.

**Finding 3: Experience Gaps**
* **Result:** Satisfaction is lowest among the diverse 20 to 39 year old demographic.
* **Recommendation:** Implement digital communication platforms for real time wait updates to raise satisfaction scores from 4.99 to a target of 7.0 out of 10.

## 6. Next Steps
* **Predictive Modeling:** Develop a machine learning model to forecast ER arrivals based on historical Monday and Saturday trends to enable proactive staffing.
* **Referral Expansion:** Apply the transition protocol developed for Orthopedics to the Physiotherapy and Cardiology departments to further reduce exit blocks.
* **Limitation:** Current data does not include acuity levels (severity of illness), which should be integrated in future iterations to refine wait time benchmarks.

## 7. Context and Credits
* **Client:** St. Jude’s Health System (Operational Excellence Division)
* **Program:** Academic Data Analytics Project
* **AI Disclosure:** AI tools were utilized for document structuring and linguistic refinement.
