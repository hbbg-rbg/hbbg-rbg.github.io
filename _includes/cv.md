I build bias-aware, edge-ready speech and language models for under-represented languages. Currently a Ph.D. candidate at the Kitami Institute of Technology , I am developing unified Multimodal, Multilingual, and Multitask (M3) transformers to ensure AI systems serve diverse linguistic identities with demographic fairness and structural equity.


## <i class="fa fa-chevron-right"></i> On-going Research
<table class="table table-hover">
<tr>
  <td class='col-md-3'> May 2025</td>
  <td><strong>WMT-2026:</strong> Experimenting M3LM TextDecoder in Indic Machine Translation Shared Task. It focuses on low-resource Indic languages from diverse language families. The focus will be on North Eastern languages like Assamese (State: Assam), Bodo (State: Assam), Mizo (State: Mizoram), Khasi (State: Meghalaya), Manipuri (State: Manipur), Kokborok (State: Tripura) and Nyishi (State: Arunachal Pradesh).</td>
</tr>
<tr>
  <td class='col-md-3'> March 2025</td>
  <td><strong>M3LM-Indic Corpus:</strong> Developing a 50K+ hour open corpus covering 23 languages, complete with emotion annotations and gender balancing, utilizing weak supervision for low-resource languages.</td>
</tr>
<tr>
  <td class='col-md-3'> October 2025</td>
  <td><strong>M3LM-Indic:</strong> A bias-aware, unified Multimodal, Multilingual, and Multitask (M3) Transformer for English and all 22 scheduled Indian languages under India's Constitution. It addresses the low-resource multilingual AI scaling crisis through depth-first specialization and para-linguistic bias-aware pre-training. </td>
</tr>

</table>


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3">Oct 2025 - Present</td>
    <td>
        <strong>Ph.D. in Multimodal AI</strong>
        <br>
       Text Information Processing Lab, Department of Co-creative Engineering, Kitami Institute of Technology, Japan.
    </td>
  </tr>
  <tr>
    <td class="col-md-3">Sep 2013 - July 2015</td>
    <td>
        <strong>M.Tech in Computational Engineering and Networking</strong>
        <br>
      Computational Engineering and Networking (CEN), Amrita School of Engineering, Coimbatore.
    </td>
  </tr>
  <tr>
    <td class="col-md-3">Sep 2009 - Apr 2013</td>
    <td>
        <strong>B.E. in Electronics and Communication Engineering</strong>
        <br>
      Anna University
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Professional Experience
<table class="table table-hover">
  <tr>
    <td class="col-md-3">Oct 2025 - Present</td>
    <td>
        <strong>Ph.D. in Multimodal AI</strong>
        <br>
       Text Information Processing Lab, Department of Co-creative Engineering, Kitami Institute of Technology, Japan.
    </td>
  </tr>

<tr>
    <td class="col-md-3">Aug 2020 - Sep 2025</td>
    <td>
        <strong>Head of Product Development</strong>
        <br>
       RBG.AI, Coimbatore, India.
    </td>
  </tr>

<tr>
    <td class="col-md-3">Mar 2018 - Jun 2020</td>
    <td>
        <strong>Chief Technology Officer & R&D Product Manager</strong>
        <br>
       Arnekt Solutions Pvt. Ltd., Pune, India
    </td>
  </tr>
  
<tr>
  <td class='col-md-3'>Dec 2016 - July 2017</td>
  <td>
    <strong>Research Scientist Analyst</strong> <br>
     Accenture Innovation Center for Analytics, Artificial Intelligence, Accenture
  </td>
</tr>

<tr>
  <td class='col-md-3'>Sep 2015 - Dec 2016</td>
  <td>
    <strong>Assistant System Engineer</strong> <br>
     Digital Enterprise Services and Solutions, Artificial Intelligence Practice, Tata Consultancy Services
  </td>
</tr>

<tr>
  <td class='col-md-3'>June 2015 - Aug 2015</td>
  <td>
    <strong>Intern</strong> <br>
     Digital Enterprise Services and Solutions, Artificial Intelligence Practice, Tata Consultancy Services
  </td>
</tr>

</table>


## <i class="fa fa-chevron-right"></i> Selected Publications <a href="https://hb-bg.github.io/blob/master/publications/selected.bib"><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<a href="https://scholar.google.co.in/citations?user=_5XB1ksAAAAJ&hl=en" class="btn btn-primary" style="padding: 0.3em;">
  <i class="ai ai-google-scholar"></i> Google Scholar
</a>

<table class="table table-hover">

<tr>
<td class="col-md-3"><img src="images/publications/distang.png"/></a> </td>
<td>
    <strong>Disentangled Speech Encoder: A Robust Encoder with Dynamic Adapter for Language Identification</strong><br>
    <strong>Barathi Ganesh HB </strong>, Jairam R, Michal Ptaszynski, Reshma U, Jyothish Lal G, Premjith B <br>
    TidyLang Odyssey 2026<br>
[<a href='javascript: none'
    onclick='$("#abs_2").toggle()'>abs</a>] [pdf]  [<a href='https://github.com/rbg-research/SpeechEncoder-TidyLang' target='_blank'>code</a>] <br>
    
<div id="abs_2" style="text-align: justify; display: none">
Spoken Language Recognition (SLR) in multilingual open set tasks is challenging due to the overlap between linguistic and speaker specific traits. Fine-tuning large foundation models distorts phonetic representations or leads to overfitting, limiting generalization to unseen speakers. To address this, we propose DisentangLID, a robust adaptation method for the TidyLang Challenge integrating a frozen dual branch backbone with a lightweight adapter and adversarial learning to enforce speaker invariant representations. The method aligns semantic representations from Wav2Vec-2.0-BERT with acoustic features from a ResNet34 encoder while preserving pretrained space. A key contribution is a controlled adaptation strategy that prevents feature drift while enabling task specific refinement. Dynamic under sampling and a two stage adversarial scheme improve robustness. The model achieves 96.01 micro and 86.92 macro accuracy on validation, and <strong>90.33</strong> micro, <strong>83.43</strong> macro accuracy on the test set.
</div>

</td>
</tr>

<tr>
<td class="col-md-3"><img src="images/publications/aura-st.png"/></a> </td>
<td>
    <strong>AURA-ST: Acoustic-Unconstrained Residual Architecture for Speech Translation.</strong><br>
    <strong>Barathi Ganesh HB </strong>, Michal Ptaszynski, Reshma U, Jairam R <br>
    IWSLT 2026<br>
[<a href='javascript: none'
    onclick='$("#abs_1").toggle()'>abs</a>] [pdf]  [<a href='https://github.com/rbg-research/IWSLT-2026-AURA-ST' target='_blank'>code</a>] <br>
    
<div id="abs_1" style="text-align: justify; display: none">
We present AURA-ST, a three-stage modular pipeline for low-resource speech-to-text translation submitted to the IWSLT 2026 African-Celtic Track~1. The architecture bypasses traditional cross-attention between audio and text modalities by treating projected acoustic representations as a native token prefix to a frozen large language model. A dual-stream encoder captures linguistic and paralinguistic features via a jointly trained semantic and a paralinguistic encoder. A convolutional subsampler then bridges the modality gap through a $4\times$ temporal compression and a linear projection into the LLM embedding space. Finally, a MLP-targeted Low-Rank Adaptation adapter fine-tunes the frozen Gemma-4-E2B backbone for translation without catastrophic forgetting of base language model knowledge. We further identify and resolve the incompatibility between standard PEFT attention-level adapter injection and the Gemma-4 Per-Layer Embedding architecture that tends to cause gradient isolation. Trained on the IWSLT 2026 Track~1 data covering Hausa, Igbo, and Yoruba, the final system achieves a best proxy teacher-forced SacreBLEU of <strong>91.29</strong> on the validation set at Phase~3, with Phase~1 speech encoder validation loss converging to <strong>0.651</strong>.
</div>

</td>
</tr>

<tr>
<td class="col-md-3"><img src="images/publications/smm4h-2025.png"/></a> </td>
<td>
    <strong>SMM4H-HeaRD 2025: LLMs in Healthcare Applications.</strong><br>
    <strong>Barathi Ganesh HB </strong>, Anthony Vijay M., Naren Kishor S., Sharmila B., Jairam R., Jyothish Lal G. <br>
    IWSLT 2026<br>
[<a href='javascript: none'
    onclick='$("#abs_1").toggle()'>abs</a>] [<a href='https://workshop-proceedings.icwsm.org/pdf/2025_63.pdf' target='_blank'>pdf</a>]  [<a href='https://github.com/rbg-research/SMM4H-2025' target='_blank'>code</a>] <br>
    
<div id="abs_1" style="text-align: justify; display: none">
This paper presents a lightweight and unified LLM-based system designed for the SMM4H 2025 Task 4: Detection of Insomnia in Clinical Notes. We adopt a single-prompt inference approach using open-source language models constrained to 4B parameters for computational efficiency. On the official test set, RBG-AI achieved an F1-score of 0.9462 (Subtask 1), 0.75 (Subtask 2A), and 0.4631 (Subtask 2B), outperforming baseline metrics. Our results highlight the effectiveness of structured prompting and hybrid rule integration in clinical NLP applications.
</div>

</td>
</tr>

</table>


## <i class="fa fa-chevron-right"></i> Teaching Experience
<table class="table table-hover">
<tr>
  <td class='col-md-1'>2017-2018, Odd</td>
  <td><strong>Deep Learning and Probabilistic Graphical Models</strong> (16CN613), TA</td>
</tr>
<tr>
  <td class='col-md-1'>2017-2018, Odd</td>
  <td><strong>Deep Learning</strong> (17AL605), TA</td>
</tr>
<tr>
  <td class='col-md-1'>2016-2017, Even</td>
  <td><strong>Deep Learning for Natural Language Processing</strong> (16CN704), TA</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Coursework
+ CN611: Computational Linear Algebra and its Applications
+ CN613: Computational Optimization Theory - Linear and Non-Linear Methods
+ CN624: Probability and Graphical Models
+ CN614: Advanced Data Structures and Algorithms
+ SLMA101: Distributed Algorithms and Optimization
+ CN733: Neural Networks and Deep Learning
+ CN709: Applied Computational Linguistics
+ CN736: Text Analytics
+ SLCN101: Deep Learning for Natural Language Processing
+ CN705: Speech Processing
+ CN622: Wavelet Theory and Pattern Classification

## <i class="fa fa-chevron-right"></i> Certifications
+ "<strong>Neural Networks and Deep Learning</strong>" acquired from deeplearning.ai through coursera.
+ "<strong>Deep Learning Using Keras</strong>" acquired from udemy.
+ "<strong>Maxima and Minima concepts : Applications of Derivatives</strong>" acquired from udemy.
+ "<strong>Deep Learning Prerequisites: The Numpy Stack in Python</strong>" acquired from udemy.
+ "<strong>Machine Learning Foundation</strong>" acquired from "Tata Consultancy Services" through Tata Consultancy Services internal certification program.
+ "<strong>Statistics and R</strong>" acquired from Harvard through edx.
+ "<strong>High-Dimensional Data Analysis</strong>" acquired from Harvard through edx.
+ "<strong>Data Mining with Weka</strong>" acquired from the University of Waikato.
+ "<strong>Hadoop Fundamentals</strong>" acquired from IBM.
+ "<strong>Spark Fundamentals</strong>" acquired from IBM.
+ "<strong>Introduction to R</strong>" acquired from DataCamp.
+ "<strong>Introduction to Data Analysis using R</strong>" acquired from Big Data University.
+ "<strong>Introduction to Python</strong>" acquired from DataCamp.

## <i class="fa fa-chevron-right"></i> International Shared Tasks Participated
+ African & Celtic Speech-to-Text Translation track (IWSLT-2026)
+ Speaker-Controlled Language Recognition (Odyssey - 2026 TidyLang)
+ Audio Encoder Capability Challenge for Large Audio Language Models (InterSpeech-2026 AECC)
+ Cross-Lingual Speaker Verification (InterSpeech-2026 TidyVoice)
+ Machine Translation (EMNLP WMT-2025)
+ Detection of insomnia in clinical notes (SMM4H-HeaRD 2025)
+ First Security and Privacy Analytics Anti-Phishing Shared Task (IWSPA-AP 2018)
+ Semantic Evaluation Exercises (SemEval-2018): Affect in Tweets
+ PAN @ Conference and Labs of Evaluation Forum (PAN-2017): Author Profiling
+ Forum for Information Retrieval and Evaluation (FIRE-2017): Gender Identification in Russian Texts (RusProfiling)
+ Forum for Information Retrieval and Evaluation (FIRE-2017) : Information Retrieval from Legal Documents (IRLeD)
+ 2nd Social Media Mining for Health Application shared task at AMIA 2017
+ Sentiment Analysis for Indian Languages (Code Mixed) SAIL 2017
+ The 8th International Cybersecurity  Data Mining Competition (CDMC-2017)
+ Semantic Evaluation Exercises (SemEval-2016): Semantic Textual Similarity
+ PAN @ Conference and Labs of Evaluation Forum (PAN-2016): Author Profiling
+ Forum for Information Retrieval and Evaluation (FIRE-2016): Mixed Script Information Retrieval (MSIR)
+ Forum for Information Retrieval and Evaluation (FIRE-2016): Consumer Health Information Search (CHIS)
+ Forum for Information Retrieval and Evaluation (FIRE-2016): Code Mixed Entity Extraction – Indian Languages (CMEE – IL)
+ Forum for Information Retrieval and Evaluation (FIRE-2014): NER - Named Entity Recognition Indian Languages
+ Named Entity rEcognition and Linking (#Micropost2015 NEEL): Named Entity Recognition and Linking


## <i class="fa fa-chevron-right"></i> Invited Talks
+ Topic: "<strong>Data Preprocessing and Feature Engineering: The Key to Successful Models</strong>" in the Faculty Development Programme at Dr. B.R. Ambedkar Institute of Technology Sri Vijyapuram Andaman & Nicobar Islands. 20, Jan 2025.
+ Topic: "<strong>Jailbreaking LLM</strong>" at Amrita University, Coimbatore. 18, October 2024. 
+ Topic: "<strong>Natural Language Processing with Deep Learning</strong>" in the Faculty Development Program (FDP) at Vidya Academy of Science & Technology, Thrissur. 20, Jan 2017.
+ Topic: "<strong>Deep Learning with Python</strong>" in the Faculty Development Program (FDP) at Mepco Schlenk Engineering College, Sivakasi. 16-17, Jan 2017.
+ Topic: "<strong>Dyanamic Mode Decomposition</strong>"  from scratch . In the workshop on <a href='https://barathiganesh-hb.github.io/cen-ddm2017/'>Data -Driven Modelling 2017</a> at Computational Engineering and Networking (CEN), Amrita School of Engineering, Coimbatore. 8-9, Jan 2017.
+ Topic: "<strong>Deep Learning for BioInformatics</strong>"  in the workshop on "DeepChem 2017: Deep Learning & NLP for Computational Chemistry, Biology & Nano-materials", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, December 22-24, 2017.
+ Topic: "<strong>Dynamic Mode Decomposition in Epidemiology</strong>" in the Workshop on "A Refresher experiential course on linear algebra and Optimization for Most Modern Signal processing and pattern classification", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, 25-11,26-11 and 27-11, 2017.
+ Topic: "<strong>Natural Language Processing for Cyber Security</strong>"  in the workshop on "AISec 2017 Workshop: Modern Artificial Intelligence (AI) and Natural Language Processing (NLP) Techniques for Cyber Security", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, Saturday, October 28, 2017.
+ Topic: "<strong>A Journey to Text Analytics and Recent Trends in Text Analytics</strong>",  TEQIP sponsored Faculty Development Program on "Research Directions in Data and Text Mining", organized by Government Engineering College, Idukki on January 2016.
+ Topic: "<strong>Advanced Analytics in Text and Data Mining</strong>",  Tata Consultancy Services sponsored Faculty Development Program on "Text and Data Mining" held at Tata Consultancy Services, Kochi on April 2016.
+ Topic: "<strong>Computation differs, not Optimization</strong>",  TEQIP Sponsored Faculty Development Program on "Contemporary Developments in Optimization Techniques and its Applications", organized by TKM College of Engineering, Kollam in May 2016.
+ Topic: "<strong>Web Mining through Data and Text Mining</strong>", Association Inauguration "ORBIT 2K16" conducted by Viswa Jyothi College of Engineering and Technology, Vazhakulam on August 2016.

## <i class="fa fa-chevron-right"></i> Workshops and Shared Tasks Conducted
+ "Generative AI" workshop for Advanced Data Science Students at St Joseph's College Of Engineering, Chennai. 01 to 07, April 2025.
+ "Generative AI from Essential AI" workshop at Sri Ramakrishna Engineering College, Coimbatore. Febrauary 23 - 24, 2024. 
+ The "AI Essentials and Fundamentals" workshop at Amrita University, Coimbatore. 20 & 21, April 2022.
+ Organized a Workshop on "DeepChem 2017: Deep Learning & NLP for Computational Chemistry, Biology & Nano-materials", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, December 22-24, 2017.
+ Organized a Workshop on "Blockchain 2017 Workshop: Blockchain and Machine Learning", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, Saturday December 16, 2017.
+ Organized a Workshop on "A Refresher experiential course on linear algebra and Optimization for Most Modern Signal processing and pattern classification", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, 25-11,26-11 and 27-11, 2017.
+ Organized a Workshop on "DeepSci 2017 Workshop: Deep Learning for Healthcare and Financial Data Analytics", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, Saturday, November 11, 2017.
+ Organized a Workshop on "AISec 2017 Workshop: Modern Artificial Intelligence (AI) and Natural Language Processing (NLP) Techniques for Cyber Security", Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University, Saturday, October 28, 2017.
+ Advisory Committee member of International Shared Task “Detecting Paraphrases in Indian Languages (DPIL)”, Conducted as a part of Forum for Information Retrieval and Evaluation – 2016 by Amrita Vishwa Vidyapeetham University.
+ Advisory Committee member of International Shared Task & Workshop on  “Machine Translation system in Indian Languages (MTIL)”, Conducted by Amrita Vishwa Vidyapeetham University.
+ Session Chair member of International Shared Task on  “Indian Native Language Identification (INLI PAN @ FIRE 2017)”, Conducted by the Department of Computational Engineering and Networking, Amrita Vishwa Vidyapeetham University.

## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
<tr>
  <td class='col-md-2'>Languages</td>
  <td markdown="1">
Python, R, Matlab
  </td>
</tr>
<tr>
  <td class='col-md-2'>Frameworks & Libraries</td>
  <td markdown="1">
NumPy, Pandas, SciPy, Scikit-learn, XGBoost, LightGBM, Speechbrain, NLTK, Spacy, Gensim, Pillow, Librosa, Soundfile, OpenCV,  Pytorch, Transformers, PEFT, Accelerate, Fairseq2, Allenai, Speechbrain, OpenAI,  Langchain, LLMLite, vLLM, ONNX, Ray, MLflow, Flask, FastAPI
  </td>
</tr>
<tr>
  <td class='col-md-2'>Database</td>
  <td markdown="1">
MySQL, Postgres, MongoDB, FAISS, Quadrant
  </td>
</tr>
<tr>
  <td class='col-md-2'>Visualization</td>
  <td markdown="1">
Matplotlib, Seaborn, Plotly, Apache Superset
  </td>
</tr>
<tr>
  <td class='col-md-2'>Cloud</td>
  <td markdown="1">
AWS (S3, SageMaker, EC2), Azure (AI Services, VMs), GCP (Vertex AI, BigQuery)
  </td>
</tr>
<tr>
  <td class='col-md-2'>Annotation & Data Labeling</td>
  <td markdown="1">
Label Studio, PWALS
  </td>
</tr>
<tr>
  <td class='col-md-2'>OS</td>
  <td markdown="1">
Linux, Windows, Mac
  </td>
</tr>
<tr>
  <td class='col-md-2'>Documentation Tools</td>
  <td markdown="1">
Libreoffice, Microsoft Office, and Latex.
  </td>
</tr>
</table>
