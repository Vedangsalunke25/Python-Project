# Python-Project
Timetable management system project
The purpose of the timetable management system project is to generate a timetable for a set of subjects and teachers based on the user's inputs. The system allows the user to specify the number of subjects and the maximum number of theory lectures per week. The generated timetable ensures that each subject is assigned the maximum number of theory lectures per week, distributed evenly across the available days.

The project consists of three main functions:

get_subjects: This function prompts the user to enter the name of each subject and the corresponding teacher. It stores the subjects and teachers in separate lists and returns them as a tuple.

generate_timetable: This function utilizes the get_subjects function to obtain the subjects and teachers. It creates a timetable represented as a dictionary with weekdays (Monday to Friday) as keys and empty lists as values. The function then iterates over the weekdays and assigns theory lectures for each day based on the given constraints. It ensures that each subject is assigned the maximum number of theory lectures per week, rotating through the list of subjects.

print_timetable: This function takes the generated timetable as input and prints it in a readable format. It displays each day of the week and the corresponding lectures (subject - teacher) scheduled for that day.

Overall, the project allows the user to input the necessary details and generates a timetable that optimizes the distribution of theory lectures across the weekdays for the given subjects and teachers.
