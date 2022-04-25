# interview_site

Проект находится в папке "first"
Если на компьютере установлен django python, запустить с помощью команды "py manage.py runserver"
Если на компьютере есть pyChar, перенести все содержимое и из репозитория открыть проектком в pyCharm папку. В Терминале с помощью компанды запустить "py manage.py runserver"

Функциональные требования:
По ответу API комментариев можно воссоздать древовидную структуру.

[
{'parent': {'id': 512, 'author_name': '2eqeq2', 'text': 'dq2eq', 'parent_id': '', 'article_id': 1}, 
	'child': None},    
 {'parent': {'id': 497, 'author_name': 'w1', 'text': 'w1', 'parent_id': '', 'article_id': 1}, 
	'child': 
		[{'parent': {'id': 498, 'author_name': 'w2', 'text': 'w2', 'parent_id': '497', 'article_id': 1}, 
			'child': 
				[{'parent': {'id': 499, 'author_name': 'w3', 'text': 'w3', 'parent_id': '498', 'article_id': 1}, 
					'child': 
						[{'parent': {'id': 500, 'author_name': 'w4', 'text': 'w4', 'parent_id': '499', 'article_id': 1}, 
							'child': None}, 
						{'parent': {'id': 501, 'author_name': 'ww3', 'text': 'ww3', 'parent_id': '499', 'article_id': 1}, 
							 'child': None}
				  		 }]
				}] (ñîäåðæèò 2 äî÷åðíèõ êîììåíòðèÿ)
 		}] (ñîäåðæèò 1 äî÷åðíèé êîììåíòðèé, ñ 2ìÿ äî÷åðíèìè êîììåíòàðèÿìè)
}, 
{'parent': {'id': 492, 'author_name': 'q', 'text': 'q', 'parent_id': '', 'article_id': 1}, 
	'child': 
		[{'parent': {'id': 493, 'author_name': 'q1', 'text': 'q1', 'parent_id': '492', 'article_id': 1}, 
			'child':
 				[{'parent': {'id': 494, 'author_name': 'q2', 'text': 'q2', 'parent_id': '493', 'article_id': 1}, 					'child': 
						[{'parent': {'id': 495, 'author_name': 'q3', 'text': 'q3', 'parent_id': '494', 'article_id': 1},
							 'child': None
						}]
				}]
		}]
}
]
