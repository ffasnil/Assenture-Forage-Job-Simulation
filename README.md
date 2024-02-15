# Assenture-Forage-Job-Simulation
![Social Buzz Accenture Project](https://github.com/ffasnil/Assenture-Forage-Job-Simulation/assets/89661712/669049bf-455e-4265-bd1b-75152d65e6cd)
links to Tableau -> [Accenture-Forage Project: Social Buzz](https://public.tableau.com/views/Accenture-ForageProjectSocialBuzz/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

</br>
</br>

This project is a part of the [Accenture Virtual Experience Program](https://www.accenture.com/gb-en/careers/local/virtual-experience-program), where a role as a specialist in Data Analytics will be undertaken. Tasks will be assigned by a client consulting with the company to uncover insights from the provided CSV files.


1) Content.csv includes 5 variables and 1,000 rows
   | **Variables** | **Data Types** | **Desciption** |
   | --------- | ---------- | ---------- |
   | Content ID | int | Identification code of content |
   | User ID | object | Identification code of user |
   | Type | object | Type of content format |
   | Category | object | Content category |
   | URL | object | URL of content |
   
</br>

2) Reactions.csv includes 4 variables and 25,553 rows
   | **Variables** | **Data Types** | **Desciption** |
   | --------- | ---------- | ---------- |
   | Content ID | int | Identification code of content |
   | User ID | object | Identification code of user |
   | Type | object | Reaction type |
   | Datetime | object | Date and time (MM/DD/YYYY HH:MM:SS) |

</br>

3) ReactionTypes.csv includes 3 variables and 16 rows
    | **Variables** | **Data Types** | **Desciption** |
   | --------- | ---------- | ---------- |
   | Type | object | Reaction type |
   | Sentiment | object | Positive, Neutral, Negative |
   | Score | int | Score of reaction |

In addition, the libraries used in this project consist of **pandas**, **seaborn**, and **matplotlib**
   
