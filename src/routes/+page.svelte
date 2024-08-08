<script lang="ts">
    import { Search, Button, Heading, P, Card, Dropdown, DropdownItem, Avatar } from 'flowbite-svelte';
    import { ArrowRightOutline, DotsHorizontalOutline } from 'flowbite-svelte-icons';
</script>

<div class="container max-w-2xl mx-auto p-5" >
    <div class="text-center">
        <Heading tag="h1" class="mb-4" customSize="text-4xl font-extrabold  md:text-5xl lg:text-6xl">Spaghetti startups</Heading>
        <P class="mb-3 text-center" color="text-gray-500 dark:text-gray-400">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet odio enim fugiat temporibus, sapiente repellat ad fugit eligendi, voluptas tenetur harum incidunt rem alias molestiae, iste hic recusandae doloremque quo!</P>
    </div>

    <div class="my-10">
        <Search>
            <Button>Search</Button>
        </Search>
    </div>
</div>

<div id="startups-list" class="container mx-auto">
    <Heading tag="h2">Last added</Heading>
    <hr class="my-2"/>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 px-6 mt-10">
        <Card padding="sm">
            <div class="flex flex-col items-center pb-4">
              <Avatar size="lg" src="https://gravatar.com/avatar/0e3be14646f60b3a6dfef41291e57d1f?s=400&d=robohash&r=x" />
              <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white"><a href="/" class="underline cursor-pointer" >Bonnie Green</a></h5>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
            </div>
        </Card>
        <Card padding="sm">
            <div class="flex flex-col items-center pb-4">
              <Avatar size="lg" src="https://gravatar.com/avatar/0e3be14646f60b3a6dfef41291e57d1f?s=400&d=robohash&r=x" />
              <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white"><a href="/" class="underline cursor-pointer" >Bonnie Green</a></h5>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
            </div>
        </Card>
        <Card padding="sm">
            <div class="flex flex-col items-center pb-4">
              <Avatar size="lg" src="https://gravatar.com/avatar/0e3be14646f60b3a6dfef41291e57d1f?s=400&d=robohash&r=x" />
              <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white"><a href="/" class="underline cursor-pointer" >Bonnie Green</a></h5>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
            </div>
        </Card>
        <Card padding="sm">
            <div class="flex flex-col items-center pb-4">
              <Avatar size="lg" src="https://gravatar.com/avatar/0e3be14646f60b3a6dfef41291e57d1f?s=400&d=robohash&r=x" />
              <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white"><a href="/" class="underline cursor-pointer" >Bonnie Green</a></h5>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
            </div>
        </Card>
        <Card padding="sm">
            <div class="flex flex-col items-center pb-4">
              <Avatar size="lg" src="https://gravatar.com/avatar/0e3be14646f60b3a6dfef41291e57d1f?s=400&d=robohash&r=x" />
              <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white"><a href="/" class="underline cursor-pointer" >Bonnie Green</a></h5>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
              <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
            </div>
        </Card>
    </div>
</div>