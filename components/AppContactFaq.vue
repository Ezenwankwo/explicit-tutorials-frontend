<template>
    <div class="bg-blue-50 py-12">
        <div class="container mx-auto">
            <div class="flex flex-col w-full lg:flex-row">
                <div class="grid flex-grow justify-center">
                    <h2 class="text-4xl font-bold">Ace Your Exams At<br> One Sitting</h2>
                    <p>Join thousands of fellow knowledge<br> enthusiasts and subscribe to
                        our weekly<br> newsletter for content alerts, research tips, and<br> more.
                    </p>
                    <div class="form-control w-full max-w-xs">
                        <label class="label">
                            <span class="label-text">Email address</span>
                        </label>
                        <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs" />
                    </div>
                </div>
                <div class="divider lg:divider-horizontal"></div>
                <div class="grid flex-grow justify-center">
                    <h2 class="text-4xl font-bold">Frequently Asked<br> Questions</h2>
                    <div class="py-6">
                        <div tabindex="0"
                            class="collapse collapse-plus border border-base-300 bg-base-100 rounded-box my-2">
                            <div class="collapse-title text-lg font-medium">
                                How can i become an affiliate?
                            </div>
                            <div class="collapse-content">
                                <p>It is a long established fact that <br>a reader will be distracted by the readable
                                    <br>
                                    content of a page when looking at its layout.
                                </p>
                            </div>
                        </div>
                        <div tabindex="0"
                            class="collapse collapse-plus border border-base-300 bg-base-100 rounded-box my-2">
                            <div class="collapse-title text-lg font-medium">
                                How can i register as a student?
                            </div>
                            <div class="collapse-content">
                                <p>It is a long established fact that <br>a reader will be distracted by the readable
                                    <br>
                                    content of a page when looking at its layout.
                                </p>
                            </div>
                        </div>
                        <div tabindex="0"
                            class="collapse collapse-plus border border-base-300 bg-base-100 rounded-box my-2">
                            <div class="collapse-title text-lg font-medium">
                                How can i pay for the courses?
                            </div>
                            <div class="collapse-content">
                                <p>It is a long established fact that <br>a reader will be distracted by the readable
                                    <br>
                                    content of a page when looking at its layout.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="text-center text-blue-700">
                        <a class="link link-hover">View all</a>
                        <Icon name="bi:caret-right-fill" />
                    </div>
                    <div class="text-center mt-8">
                        <span>Can’t find what you’re looking for?</span>
                        <NuxtLink to="/contact" class="text-blue-700 ml-4"> Contact Us</NuxtLink>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>