# Emergency Department Operational Performance & Patient Experience Analytics

## 1. Executive Summary

<img width="993" height="698" alt="Screenshot 2026-01-12 at 6 52 35 PM" src="https://github.com/user-attachments/assets/55fc1e5b-e6db-4ff7-b6fe-387533e41744" />

**The Business Problem:** St. Jude’s Health System faced a critical misalignment between Emergency Department staffing and patient demand, resulting in an average satisfaction score of 4.99 out of 10 and a 35.3-minute average wait time.

**The Failing Decision:** Hospital leadership was utilizing rigid staffing rosters that failed to synchronize with predictable surge patterns, causing "exit blocks" and high-density arrival windows for a core demographic of 2,388 young adults.

**Scale of Impact:** Operational bottlenecks in General Practice and Orthopedics referrals, combined with poor communication clarity for 1,951 African American and 1,557 Multiracial patients, put community trust and institutional performance targets at risk.

**The Outcome:** This project delivered a three tier Power BI reporting suite that identifies high density arrival windows. The implementation provides a roadmap to reduce wait times by 15 percent and raise patient satisfaction to a 7.0 benchmark through data driven roster optimization.


## 2. Business Problem
**The Decision Framework:** The organization was repeatedly making staffing and resource allocation decisions based on static institutional hours rather than dynamic clinical demand cycles.

**Flawed Logic:** The previous model assumed a uniform distribution of patients. This logic was flawed as it ignored concentrated spikes on Mondays (1,377 patients) and Saturdays (1,322 patients), as well as daily surges at 11:00, 13:00, 19:00, and 23:00.

**Operational Failure:** This lack of alignment forced a limited number of staff to manage high density windows, directly causing the 35.3-minute wait time. Furthermore, the efficiency of the department was constrained by the response times of General Practice and Orthopedics, which account for 65 percent of all specialist transitions.

## 3. Methodology
The project utilized a structured analytical approach to transform raw clinical data into executive insights:
* **Data Engineering:** Processed 9,216 patient records in Power Query to normalize demographics and extract temporal features from admission timestamps.
* **Tiered Architecture:** Developed a three page Power BI solution tailored to specific stakeholder needs:
    * **Consolidated View:** High level KPIs for C-Suite oversight of wait times and satisfaction.
    * **Monthly Operational View:** A temporal demand heatmap for Nurse Unit Managers to optimize rosters.
    * **Patient Details:** A granular drill through interface for Quality Assurance root cause analysis.
* **Metric Development:** Engineered DAX measures for Admission Rate percentages and demographic specific satisfaction benchmarks.

## 4. Demonstration of Skills and Capabilities

**Operational Synchronicity Analysis:**
I identified that ER demand follows a predictable cycle. By mapping 9,216 visits, I isolated Monday as the busiest day. This proves the capability to provide HR with the exact timestamps (11:00, 13:00, 19:00, 23:00) required for roster optimization.

**Clinical Flow & Resource Mapping:**
I quantified systemic bottlenecks by identifying that while 5,400 patients require no intervention, 2,835 patients require specialist redirection. I localized the pressure to General Practice (1,840) and Orthopedics (995), demonstrating the ability to identify "exit blocks" in a complex system.

**Demographic Experience Strategy:**
I isolated the 20 to 39 year old cohort (2,388 patients) and cross referenced their 4.99 satisfaction score against ethnic profiles. This demonstrates a capability to advocate for "Experience Equity" through data, identifying specific service gaps for 1,951 African American and 1,557 Multiracial patients.



## 5. Results & Business Recommendations

**Finding 1: Structural Misalignment of Staffing**
* **Result:** Labor allocation is currently out of sync with peak arrival hours on Mondays and Saturdays.
* **Targeted KPI:** Redesign shift rosters to reduce average wait time from **35.3 minutes to under 30 minutes** (a 15% efficiency gain).

**Finding 2: Specialist Transition Bottlenecks**
* **Result:** General Practice and Orthopedics account for 65 percent of transitions, causing bed occupancy delays.
* **Targeted KPI:** Establish priority consultation protocols to achieve a **20% increase in bed turnover rate** for the 2,835 patients requiring specialist care.

**Finding 3: Service Gaps in Core Demographics**
* **Result:** A score of 4.99/10 indicates a communication failure for the primary 20 to 39 year old patient base.
* **Targeted KPI:** Implement digital communication platforms to increase the Satisfaction Score to a **minimum of 7.0 out of 10** and achieve a **90% positive feedback rate** on communication clarity.

## 6. Next Steps
* **Predictive Staffing:** Integrate machine learning to forecast arrival surges 24 hours in advance.
* **Communication Audit:** Conduct a qualitative review of the digital text update platform to ensure it meets the needs of the diverse patient base.
* **Limitation:** The current dataset lacks "Acuity" or "Triage Level" markers: future versions should weigh wait times against medical urgency.

## 7. Context and Credits
* **Client:** St. Jude’s Health System (Operational Excellence Division)
* **Program:** Academic Data Analytics Project
* **AI Disclosure:** AI tools were utilized for document structuring, KPI elevation, and linguistic refinement.
