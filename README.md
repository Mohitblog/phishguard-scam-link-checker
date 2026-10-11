# phishguard-scam-link-checker
Built a web app that checks suspicious links from SMS, email and WhatsApp and explains in plain language why they look risky. It combines a 15-rule checker with a Logistic Regression model (scikit-learn, 26 URL features) and shows which features influenced each result. Includes batch checking, a JSON API and a clean responsive interface. Never labels a link as “safe”, because it only analyses the text of the link.
Tech: Python, Flask, scikit-learn, HTML/CSS, unittest
