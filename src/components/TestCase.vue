<script setup lang="ts">
import { Tabs, TabsList, TabsTrigger, TabsContent } from '@/components/ui/tabs';
</script>

<template>
    <div class="h-full w-full flex flex-col justify-between">
        <div class="flex flex-col mx-5 my-4 space-y-4">
            <Tabs default-value="testCase1">
                <TabsList>
                    <TabsTrigger value="testCase1">
                        Case 1
                    </TabsTrigger>
                    <TabsTrigger value="testCase2">
                        Case 2
                    </TabsTrigger>
                    <TabsTrigger value="testCase3">
                        Case 3
                    </TabsTrigger>
                </TabsList>
                <TabsContent value="testCase1">
                    Here is Case 1
                </TabsContent>
                <TabsContent value="testCase2">
                    Here is Case 2
                </TabsContent>
                <TabsContent value="testCase3">
                    Here is Case 3
                </TabsContent>
            </Tabs>
        </div>
    </div>
</template>