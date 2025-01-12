## Project Name: BrochureGen: Multilingual Brochure Generator for Enterprises

### Overview
```
BrochureGen is a cutting-edge tool that helps businesses such as NVIDIA craft professional and high-quality brochures for potential clients, investors, and recruits. 
This solution employs advanced large language models and OpenAI technologies to create engaging, customized brochures, which can be easily translated into various languages.\
Currently, it supports Arabic, Hebrew, and Japanese, enhancing global outreach and promoting effective communication with diverse audiences.\
This project focuses on optimising the brochure creation process by automating content generation, translation, and formatting. This enables businesses to swiftly expand\
their marketing reach across diverse regions and languages.
```
#### Key Features
```
•	AI-Powered Content Creation: Automatically generates text for brochures based on input from the user, including company profile, product features, and recruitment details.
•	Multilingual Support: Translates brochures into multiple languages, including built-in support for Arabic, Hebrew, and Japanese, utilising large language models and AI translation technologies.
•	Customizable Templates: This service offers a range of attractive templates for businesses to design brochures, catering to various needs (clients, investors, recruits).
•	Scalable Solution: Scales easily for companies looking to generate brochures for different regions or business divisions, saving time and resources
```



#### Technologies Used
```
•	OpenAI GPT-3 / GPT-4: For content generation and AI-driven language translation.
```

#### Installation
```
import os
import requests
from dotenv import load_dotenv
from bs4 import BeautifulSoup
from IPython.display import Markdown, display
from openai import OpenAI
```

#### Processes
```
initialise and constants
create class to represent a Webpage
Create system prompts
create function def get_links_user_prompt(website)
create function def get_brochure_user_prompt(company_name, url)
create function def create_brochure_language(company_name, url, language)

```

#### Contribution
```
We welcome contributions! To contribute, please fork the repository and submit a pull request. Before contributing, please make sure that:
•	Your code follows the project's coding style.
•	You have written tests for any new features or bug fixes.
•	Documentation is updated with any new functionality.

```

#### Credit
```
I am setting on the gaint shoulder of developers.
Special thanks to Edward Donner
```


#### Licence
```
Copyright (C) 2025 David Gabriel
```

#### References
```
https://edwarddonner.com/2024/11/13/llm-engineering-resources/
https://platform.openai.com/api-keys
https://www.deeplearning.ai/courses/
www.nvidia.com](https://www.nvidia.com/en-au/
...



