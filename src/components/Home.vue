<template>
	<div>
		<div class="h-screen flex">
			<div class="bg-gray-100  w-64 border-r px-8 py-4 overflow-auto">
				<svg class="h-10 w-10" viewBox="0 0 512.049 512.049" style="enable-background:new 0 0 512.049 512.049;" xml:space="preserve">
					<g>
						<path style="fill:#E64A19;" d="M256.054,0.012c-26.442,0.001-52.724,4.103-77.909,12.16c-4.427,1.413-7.43,5.529-7.424,10.176
							v116.928c-0.002,5.891,4.772,10.668,10.663,10.67c2.043,0.001,4.044-0.586,5.764-1.689c59.575-38.056,138.72-20.612,176.776,38.963
							s20.612,138.72-38.963,176.776c-59.575,38.056-138.72,20.612-176.776-38.963c-13.167-20.611-20.152-44.564-20.13-69.022V53.708
							c0.057-5.891-4.673-10.712-10.563-10.769c-2.191-0.021-4.335,0.633-6.141,1.873C-5.292,124.713-35.077,284.044,44.824,400.686
							s239.231,146.427,355.874,66.526s146.427-239.231,66.526-355.874C419.503,41.673,340.497,0.022,256.054,0.012z"/>
						<circle style="fill:#E64A19;" cx="256.054" cy="256.012" r="85.333"/>
					</g>
				</svg>
				<nav class="mt-8">
					<h2 class="uppercase font-semibold text-gray-600 tracking-wide text-xs">Issues</h2>
					<div class="mt-2 -mx-2">
						<a href="#" class=" flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium bg-gray-200 rounded-lg">
							<span>All</span>
							<span class="text-xs text-gray-700 font-semibold">36</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Assgined to me</span>
							<span class="text-xs text-gray-700 font-semibold">2</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Create by me</span>
							<span class="text-xs text-gray-700 font-semibold">1</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Archived</span>
						</a>
					</div>
					<h2 class="uppercase font-semibold text-gray-600 tracking-wide text-xs mt-8">Tags</h2>
						<div class="mt-2 -mx-2">
						<a href="#" class=" flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium bg-gray-200 rounded-lg">
							<span>Bugs</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Featured Request</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Marketing</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>v2.0</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Enhancement</span>
						</a>
						<a href="#" class="mt-4 flex items-center justify-between px-3 py-1 text-sm text-gray-900 font-medium rounded-lg">
							<span>Design</span>
						</a>
						<button class="flex items-center mt-3 text-sm text-gray-600 ml-2">
							<svg viewBox="0 0 24 24" class="fill-current h-5 w-5 text-gray-500">
								<path d="M17 11a1 1 0 0 1 0 2h-4v4a1 1 0 0 1-2 0v-4H7a1 1 0 0 1 0-2h4V7a1 1 0 0 1 2 0v4h4z"/>
							</svg>
							<span class="">New Project</span>
						</button>
					</div>
				</nav>
			</div>
			<div class="flex-1 min-w-0 flex flex-col bg-white">
				<div class="flex-shrink-0 border-b-2 border-gray-200">
						<header class="px-6">
							<div class="flex justify-between items-center py-3 border-b border-gray-200">
								<div class="">
									<div class="relative w-64">
										<span class="absolute inset-y-0 left-0 pl-3 flex items-center">
											<svg class="fill-current h-6 w-6 text-gray-600" viewBox="0 0 24 24">
												<path d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/>
											</svg>
										</span>
										<input class="block w-full rounded border border-gray-400 pr-4 py-2 text-sm pl-10 text-gray-900 placeholder-gray-600" placeholder="Search">
									</div>
								</div>
								<div class="flex items-center">
									<button>
										<svg viewBox="0 0 24 24" class="fill-current text-gray-500 h-6 w-6">
											<path d="M15 19a3 3 0 0 1-6 0H4a1 1 0 0 1 0-2h1v-6a7 7 0 0 1 4.02-6.34 3 3 0 0 1 5.96 0A7 7 0 0 1 19 11v6h1a1 1 0 0 1 0 2h-5zm-4 0a1 1 0 0 0 2 0h-2zm0-12.9A5 5 0 0 0 7 11v6h10v-6a5 5 0 0 0-4-4.9V5a1 1 0 0 0-2 0v1.1z"/>
										</svg>
									</button>
									<button class="ml-6">
											<img class="w-6 h-6 rounded-full object-cover" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
									</button>
								</div>
							</div>
							<div class="flex items-center justify-between py-2">
								<div class="flex items-center">
									<h2 class="text-2xl font-semibold text-gray-900 leading-tight">All issues</h2>
									<div class="ml-6 flex items-center">
										<span class="rounded-full border-2 border-white">
											<img class="w-6 h-6 rounded-full object-cover" src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
										</span>
										<span class="-ml-2 rounded-full border-2 border-white">
											<img class="w-6 h-6 rounded-full object-cover" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
										</span>
										<span class="-ml-2 rounded-full border-2 border-white">
											<img class="w-6 h-6 rounded-full object-cover" src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&auto=format&fit=facearea&facepad=2.25&w=144&h=144&q=80" alt=""> 
										</span>
										<span class="-ml-2 rounded-full border-2 border-white">
											<img class="w-6 h-6 rounded-full object-cover" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&auto=format&fit=facearea&facepad=2.25&w=144&h=144&q=80" alt="">
										</span>
									</div>
								</div>
								<div class="flex">
									<span class="inline-flex p-1 border bg-gray-200 rounded">
										<button class="px-2 py-1 rounded">
											<svg class="h-6 w-6 text-gray-600" viewBox="0 0 24 24">
												<path stroke="currentColor" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"/>
											</svg>
										</button>
										<button class="px-2 py-1 bg-white rounded shadow">
											<svg class="h-6 w-6 text-gray-600" viewBox="0 0 24 24">
												<path stroke="currentColor" d="M5 3h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5c0-1.1.9-2 2-2zm14 8V5H5v6h14zm0 2H5v6h14v-6zM8 9a1 1 0 1 1 0-2 1 1 0 0 1 0 2zm0 8a1 1 0 1 1 0-2 1 1 0 0 1 0 2z"/>
											</svg>
										</button>
									</span>
									<button class="ml-5 flex items-center text-sm bg-gray-800 py-2 pr-4 pl-2 rounded-lg text-white ml-2 hover:bg-gray-700">
										<svg viewBox="0 0 24 24" class="fill-current h-6 w-6 text-gray-300">
											<path d="M17 11a1 1 0 0 1 0 2h-4v4a1 1 0 0 1-2 0v-4H7a1 1 0 0 1 0-2h4V7a1 1 0 0 1 2 0v4h4z"/>
										</svg>
										New Issue
									</button>
								</div>
							</div>
						</header>
					</div>
					<div class="flex-1 overflow-auto">
						<main class="p-3 flex">
							<div class="p-3 flex-shrink-0 w-80 bg-gray-100 rounded">
								<h3 class="text-sm font-medium text-gray-700">Backlog</h3>
								<ul class="mt-2">
									<li class="">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
								</ul>
							</div>
							<div class="p-3 flex-shrink-0 ml-3 w-80 bg-gray-100 rounded">
								<h3 class="text-sm font-medium text-gray-700">In Progress</h3>
								<ul class="mt-2">
									<li class="">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
								</ul>
							</div>
							<div class="p-3 flex-shrink-0 ml-3 w-80 bg-gray-100 rounded">
								<h3 class="text-sm font-medium text-gray-700">Ready for Review</h3>
								<ul class="mt-2">
									<li class="">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
								</ul>
							</div>
							<div class="p-3 flex-shrink-0 ml-3 w-80 bg-gray-100 rounded">
								<h3 class="text-sm font-medium text-gray-700">Done</h3>
								<ul class="mt-2">
									<li class="">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
									<li class="mt-3">
										<a href="#" class="block p-5 bg-white rounded shadow ">
											<div class="flex items-center justify-between">
												<p class="text-sm font-medium text-gray-900">Add discount code to checkout page</p>
												<span>
													<img class="rounded-full w-6 h-6 " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=faceare&facepad=2&w=144&h=144&q=60" alt="">
												</span>
											</div>
											<div class="flex justify-between items-baseline">
												<div class="text-sm text-gray-500">
													<time datetime="2019-09-14">
														Sep 14
													</time>
												</div>
												<div class="mt-2">
												<span class="px-2 py-1 leading-tight inline-flex items-center bg-teal-100 rounded">
													<svg class="h-2 w-2 text-teal-500" viewBox="0 0 8 8" fill="currentColor">
														<circle cx="4" cy="4" r="3"/>
													</svg> 
													<span class="ml-2 text-sm font-medium text-teal-900">Feature Request</span>
												</span>
												</div>
											</div>
										</a>
									</li>
								</ul>
							</div>
						</main>
					</div>
			</div>
		</div>
	</div>
</template>
<script>
export default {
	name: 'Home',
}
</script>

<style src="../assets/tailwind.css"></style>