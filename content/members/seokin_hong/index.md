---
layout: personal_info  # FIXED! DO NOT CHANGE!
author: Seokin Hong    # your name
title:  Seokin Hong    # your name
date:   2024-06-06

images: [
    images/members/seokin_hong.png  # your profile image path (relavant to assets/)
]

params:
    position:  "Principal Investigator"  # one of ["Principal Investigator", "PhD Course", "Master Course", "Graduate"]
    job_title: "Assistant Professor"     # all of the students should specify the title of himself as a "Researcher"
    telephone: "+82-31-299-4915"         # phone number (if you don't want to upload your phone number, comment or remove this line!)
    email:     "seokin@skku.edu"         # school email address

    interests: [   # fill out your research interests
        "Computer Architecture", 
        "Memory Systems"
    ]

    biography: |   # fill out your short biography... Introduce yourself!
        I am an Assistant Professor in the Department of Semiconductor Systems Engineerings at Sungkyunkwan University (SKKU). My major research experiences and interests include the design of low power, reliable, and high-performance microarchitectures and memory systems. I received the PhD in Computer Science from KAIST, Korea, in 2015. Prior to joining SKKU, I was a Research Scientist at IBM TJ Watson Research Center and a Senior Engineer at Samsung Electronics.

    enable_sections:
        enable_experiences:   true
        enable_awards_honers: true
        enable_activities:    true
        enable_publications:  true

    experiences:
        - {
            exp_from: "2021",
            exp_to:   "",
            exp_desc: "Assistant Professor at Sungkyunkwan University"
        }
        - {
            exp_from: "2018",
            exp_to:   "2021",
            exp_desc: "Assistant Professor at Kyungpook National University"
        }
        - {
            exp_from: "2017",
            exp_to:   "2018",
            exp_desc: "Research Scientist at IBM T.J. Watson Research Center"
        }
        - {
            exp_from: "2015",
            exp_to:   "2017",
            exp_desc: "Senior Engineer at Samsung Electronics"
        }
        - {
            exp_from: "2008",
            exp_to:   "2015",
            exp_desc: "Research Assistant at KAIST"
        }
        - {
            exp_from: "2009",
            exp_to:   "2009",
            exp_desc: "Research Intern at ETRI"
        }
        - {
            exp_from: "2006",
            exp_to:   "2008",
            exp_desc: "Software Engineer Intern at SSM (Samsung Software Membership)"
        }

    awards_honer:
        - 2014 Best Paper Nominee, IEEE International Conference on Computer Design (ICCD'14)
        - 2013 Best Paper Award, Design Automation and Test in Europe Conference (DATE’13)
        - 2010 Best Paper Award, IEEE International Conference on Computer Design (ICCD’10)

    activities:
        - {
            act_type: "Editorial Board Member",
            act_desc: "IEMEK Journal of Embedded Systems and Applications"
        }
        - {
            act_type: "Program Committee",
            act_desc: "International Symposium on High-Performance Computer Architecture (HPCA 2024)"
        }
        - {
            act_type: "Program Committee",
            act_desc: "IEEE International Conference on Computer Design (ICCD 2019)"
        }
        - {
            act_type: "Reviewer",
            act_desc: "IEEE International Conference on Computer Design (ICCD)"
        }
        - {
            act_type: "Reviewer",
            act_desc: "The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC)"
        }
        - {
            act_type: "Reviewer",
            act_desc: "The International Symposium on Low Power Electronics and Design (ISLPED)"
        }
        - {
            act_type: "Reviewer",
            act_desc: "ACM Transaction on Architecture and Code Optimization"
        }
        - {
            act_type: "Reviewer",
            act_desc: "IEEE Transaction on Computer"
        }
        - {
            act_type: "Reviewer",
            act_desc: "IEEE Transaction on Computer-Aided Design of Integrated Circuits and Systems"
        }
        - {
            act_type: "Reviewer",
            act_desc: "IEEE Computer Architecture Letters"
        }
        - {
            act_type: "Reviewer",
            act_desc: "ETRI Journal"
        }
        - {
            act_type: "Reviewer",
            act_desc: "IEEE Access"
        }
        

    publications:
        - {
            pub_title: "SAVector: Vectored Systolic Arrays",
            pub_venue: "IEEE Access",
            pub_date:  "2024-03-25",
            pub_url:   ""
        }
        - {
            pub_title: "Facto-CNN: Memory-Efficient CNN Training with Low-rank Tensor Factorization and Lossy Tensor Compression",
            pub_venue: "15th Asian Conference on Machine Learning (ACML)",
            pub_date:  "2024-02-27",
            pub_url:   ""
        }
        - {
            pub_title: "Conveyor: Towards Asynchronous Dataflow in Systolic Array to Exploit Unstructured Sparsity",
            pub_venue: "2023 IEEE 41st International Conference on Computer Design (ICCD)",
            pub_date:  "2023-11-06",
            pub_url:   "/publications/231106-conveyor-sa/"
        }
---