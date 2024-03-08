<template>
	<button type="button" class="btn btn-default">Add</button>
	<table class="table">
		<thead>
			<tr>
				<th scope="col">#</th>
				<th scope="col">Task name</th>
				<th scope="col">Status</th>
				<th scope="col">Edit</th>
				<th scope="col">Remove</th>
			</tr>
		</thead>
		<tbody>
			<task v-for="(task, index) in tasks" :key="task.id"></task>
		</tbody>
	</table>
</template>

<script></script>

<style></style>

<!-- <div class="header">
		<h1>TODO List Demo App</h1>
		<label>Do it now.</label>
	</div>
	<div class="table">
		<button type="button" class="btn btn-default">Add</button>
		<table class="table">
			<thead>
				<tr>
					<th scope="col">#</th>
					<th scope="col">Task name</th>
					<th scope="col">Status</th>
					<th scope="col">Edit</th>
					<th scope="col">Remove</th>
				</tr>
			</thead>
			<tbody>
				
				<tr>
					<th scope="row">25</th>
					<td>Send Email</td>
					<td>
						<button type="button" class="btn btn-default">In Progress</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span
								class="glyphicon glyphicon-pencil"
								aria-hidden="true"
							></span>
						</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span class="glyphicon glyphicon-trash" aria-hidden="true"></span>
						</button>
					</td>
				</tr>
				<tr>
					<th scope="row">24</th>
					<td>Finish Assignment</td>
					<td>
						<button type="button" class="btn btn-default">Complete</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span
								class="glyphicon glyphicon-pencil"
								aria-hidden="true"
							></span>
						</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span class="glyphicon glyphicon-trash" aria-hidden="true"></span>
						</button>
					</td>
				</tr>
				<tr>
					<th scope="row">24</th>
					<td>Bake Cake</td>
					<td>
						<button type="button" class="btn btn-default">Todo</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span
								class="glyphicon glyphicon-pencil"
								aria-hidden="true"
							></span>
						</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span class="glyphicon glyphicon-trash" aria-hidden="true"></span>
						</button>
					</td>
				</tr>
				<tr>
					<th scope="row">24</th>
					<td>Write Blog Post</td>
					<td>
						<button type="button" class="btn btn-default">In Progress</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span
								class="glyphicon glyphicon-pencil"
								aria-hidden="true"
							></span>
						</button>
					</td>
					<td>
						<button type="button" class="btn btn-default">
							<span class="glyphicon glyphicon-trash" aria-hidden="true"></span>
						</button>
					</td>
				</tr>
			</tbody>
		</table>
	</div> -->
