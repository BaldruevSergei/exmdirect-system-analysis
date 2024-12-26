# Сущности и их поля (Entity Description)

## User
| Поле | Тип |
|------|-----|
| id | Long |
| username | String |
| password | String |
| role | UserRole |

## UserRole
| Поле | Тип |
|------|-----|
| id | Long |
| name | String |

## Student
| Поле | Тип |
|------|-----|
| id | Long |
| user | User |
| schoolClass | SchoolClass |

## Teacher
| Поле | Тип |
|------|-----|
| id | Long |
| user | User |
| subjects | List<Subject> |

## Admin
| Поле | Тип |
|------|-----|
| id | Long |
| user | User |

## SchoolClass
| Поле | Тип |
|------|-----|
| id | Long |
| name | String |
| students | List<Student> |

## ClassSubject
| Поле | Тип |
|------|-----|
| id | Long |
| schoolClass | SchoolClass |
| subject | Subject |

## Subject
| Поле | Тип |
|------|-----|
| id | Long |
| name | String |

## Exam
| Поле | Тип |
|------|-----|
| id | Long |
| subject | Subject |
| lessonTopic | LessonTopic |
| questions | List<Question> |

## LessonTopic
| Поле | Тип |
|------|-----|
| id | Long |
| name | String |

## Question
| Поле | Тип |
|------|-----|
| id | Long |
| questionText | String |
| questionType | QuestionType |
| answers | List<Answer> |

## QuestionType
| Поле | Тип |
|------|-----|
| id | Long |
| type | String |

## Answer
| Поле | Тип |
|------|-----|
| id | Long |
| text | String |
| isCorrect | Boolean |

## StudentExam
| Поле | Тип |
|------|-----|
| id | Long |
| student | Student |
| exam | Exam |
| score | Double |
