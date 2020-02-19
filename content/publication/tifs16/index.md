---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detecting Facial Retouching Using Supervised
Deep Learning"
authors: ["admin", R. Singh, M. Vatsa, K. W. Bowyer]
date: 2020-02-18T21:18:26-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-18T21:18:26-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Information Forensics and Security"
publication_short: "T-IFS"

abstract: "Digitally altering, or retouching, face images is a common practice for images on social media, photo sharing websites, and even identification cards when the standards are not strictly enforced. This research demonstrates the effect of digital alterations on the performance of automatic face recognition, and also introduces an algorithm to classify face images as original or retouched with high accuracy. We first introduce two face image databases with unaltered and retouched images. Face recognition experiments performed on these databases show that when a retouched image is matched with its original image or an unaltered gallery image, the identification performance is considerably degraded, with a drop in matching accuracy of up to 25%. However, when images are retouched with the same style, the matching accuracy can be misleadingly high in comparison with matching original images. To detect retouching in face images, a novel supervised deep Boltzmann machine algorithm is proposed. It uses facial parts to learn discriminative features to classify face images as original or retouched. The proposed approach for classifying images as original or retouched yields an accuracy of over 87% on the data sets introduced in this paper and over 99% on three other makeup data sets used by previous researchers. This is a substantial increase in accuracy over the previous state-of-the-art algorithm, which has shown <;50% accuracy in classifying original and retouched images from the ND-IIITD retouched faces database."

# Summary. An optional shortened abstract.
summary: ""

tags: ["retouching", "face recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
