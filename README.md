# Semantic Similarity with Theological Enhancement (SSTE): A Non-Technical Explanation

The Semantic Similarity with Theological Enhancement (SSTE) model is a specialized computer tool designed to help Bible readers discover Christ-centered connections throughout Scripture. 
Here's what it does in simple terms:

## What It Is
SSTE is like a special pair of "gospel-centered glasses" for reading the Bible. When you look at an Old Testament passage, these glasses help you see how it might connect to Jesus Christ in the New Testament.

## Project Approach
* Two-week iterations with defined milestones
* Incremental development with regular testing
* Focus on core functionality first, then refinement
### Testing Strategy
Testing will be pragmatic and focused:
* Manual testing of core functionality
* Automated unit tests for critical components only
* Limited user testing in the final phase
### Documentation Requirements
Documentation will be minimal but sufficient:
* Code comments for key algorithms
* Basic setup and usage instructions
* Simple API documentation
### Deliverables
1. Functional Web Application: A working web interface demonstrating Christ-centered connection detection
2. ML Model: Trained model for identifying Christ-centered connections
3. Source Code: Well-organized, commented code repository
4. Basic Documentation: Setup instructions and usage guide
5. Demo Dataset: Sample passages with identified Christ connections

## Project Plan: Incorporating Goldsworthy's Hermeneutical Framework with Marvel.bible using Machine Learning
### Understanding the Framework and Resources
* Examine Goldsworthy's hermeneutical framework from provided documents
* Explore Marvel.bible repository structure and resources
* Identify key components of Marvel.bible that can be leveraged for ML integration
* Analyze sample content to understand practical application
### Planning the Integration
* Identify machine learning opportunities within the Goldsworthy framework
* Design ML integration architecture
* Develop detailed project implementation plan
* Create comprehensive project documentation
### Deliverables
* Final project plan document
* Architecture diagram for ML integration
* Implementation roadmap with timeline
* Resource requirements and technical specifications

## How It Works

**Understanding Meaning:** First, the system learns the meaning of Bible passages by reading thousands of verses and understanding how words relate to each other.
**Finding Similarities:** When you select an Old Testament passage, the system looks for New Testament passages that share similar themes, words, or concepts.
**Adding Theological Knowledge:** Unlike regular search tools, SSTE has been taught specific theological principles from Goldsworthy's gospel-centered approach. It knows to prioritize connections that point to Jesus as the center of biblical interpretation.
**Weighing Connections:** The system gives higher importance to certain types of connections:

* Direct quotations of the Old Testament in the New Testament
* Messianic themes and prophecies
* Passages that share similar redemptive themes


## Real-World Example
If you were reading Psalm 22 with its cry of "My God, my God, why have you forsaken me?", the SSTE system would:

* Recognize this as an important messianic psalm
* Identify its connection to Jesus's words on the cross in Matthew 27:46
* Show you how other parts of the psalm (like "they divide my garments") also connect to the crucifixion narrative
* Provide insight into how this psalm fits within the broader gospel story

Simply put, SSTE is a Bible study assistant that helps you read Scripture the way Jesus taught his disciples on the road to Emmaus - seeing how all the Scriptures point to Him and His redemptive work.

## Technical Information (For Developers)

This project implements a machine learning model that combines:
* BERT-based semantic embeddings fine-tuned on biblical texts
* A knowledge graph of theological concepts
* Custom weighting algorithms for Christ-centered connections

### Tech stack:
* Python 3.9+
* PyTorch & Transformers
* Flask API
* SQLite database

## Project Status

This project is currently in early development following the implementation roadmap. Installation instructions and detailed documentation will be added as the project progresses.

## Getting Started (For Developers)

Detailed installation instructions will be provided once the initial development phases are complete. Currently, the project requires:

* Python 3.9+
* Conda environment

Check back soon for complete setup instructions.
