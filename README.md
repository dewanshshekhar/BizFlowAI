# BizFlowAI

### **README File**

---

# **BizFlowAI**  
**AI-Powered Product Planning & Talent Matching Platform**  

---

## **Overview**  
BizFlowAI is a **SaaS platform** designed to help companies **plan new products/features**, **predict costs**, and **automate talent matching**. It leverages AI to recommend tech stacks, predict project costs, and match candidates based on their skills and experience. Additionally, it provides **salary benchmarking** to ensure competitive offers and uses **Gemini API** for personalized candidate communication.  

---

## **Key Features**  
1. **Tech Stack Recommender**: Suggests optimal tools and frameworks for new projects.  
2. **Skill List Generator**: Lists required skills for the suggested tech stack.  
3. **Pricing Predictor**: Predicts project costs using an ML model trained on historical data.  
4. **Talent Ranker**: Matches resumes from a database and assigns % match scores.  
5. **Salary Mapping**: Maps applicant's past salaries to the company's pay scale.  
6. **Personalized Emails**: Sends dynamic, personalized emails to candidates using Gemini API.  
7. **Candidate Segmentation**:  
   - **Overqualified (>95%)**: Suggests senior roles.  
   - **Well-matched (80-95%)**: Sends acceptance emails.  
   - **Underqualified (50-80%)**: Provides skill improvement tips.  
   - **Rejected (<50%)**: Sends polite rejection emails.  

---

## **Tech Stack**  
- **Frontend**: Next.js (React framework for SSR + SEO).  
- **Backend**: Node.js (Express.js for API).  
- **Database**: PostgreSQL (structured data) + MongoDB (unstructured data).  
- **AI/ML**:  
  - Scikit-learn (ML model for price prediction).  
  - spaCy/NLTK (resume parsing).  
  - Gemini API (email generation).  
- **Cloud**: AWS/Azure (hosting, S3 for storage).  
- **Auth**: NextAuth.js (OAuth 2.0/JWT).  

---

## **Usage**  
1. **Company Input**:  
   - Enter project details (e.g., feature description, budget, timeline) via the UI or API.  
2. **Tech Stack & Skills**:  
   - View AI-recommended tech stacks and required skills.  
3. **Cost Prediction**:  
   - Get an estimated project cost based on historical data.  
4. **Talent Matching**:  
   - Upload resumes or connect to a resume database.  
   - View % match scores for each candidate.  
5. **Email Automation**:  
   - Send personalized emails to candidates based on their match score.  

---

## **Future Enhancements**  
1. **Product Pricing Prediction**: Predict market prices for new features/products.  
2. **Upskilling Recommendations**: Suggest courses for underqualified candidates.  
3. **Freelance Gig Matching**: Connect companies with freelancers for short-term projects.  
4. **API Licensing**: Allow third-party platforms to integrate FeatureForge's AI tools.  

---

## **License**  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

## **Acknowledgments.**  
- **Gemini API** for dynamic email generation.  
- **Scikit-learn** for ML-based price prediction.  
- **Next.js** for seamless frontend development.  

--- 

**BizFlowAI**: Empowering companies to build better products with AI-driven insights! 🚀
