Meu nome é Pedro Barros Agostini spu do lab 7


Rotas:

Route::get('/tasks', [TaskController::class, 'index']); --> Puxar todas tarefas
Route::post('/tasks', [TaskController::class, 'store']);  --> Postar novas tarefas 
Route::get('/tasks/{task}', [TaskController::class, 'show']);  --> Puxar tarefas expecíficas (filtro)
Route::put('/tasks/{task}', [TaskController::class, 'update']); --> atualizar tarefas existentes
Route::delete('/tasks/{task}', [TaskController::class, 'destroy']); --> deletar tarefas
