<template>
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <div class="panel panel-default">
                    <div class="panel-heading">Example Component</div>

                    <div class="panel-body">
                        I'm an example component!
                    </div>
                    <table class="table">
                    <tr>
                        <td>test</td>
                        <td>test</td>
                    </tr>
                    <tr>
                        <td>blah blah</td>
                        <td>blah blah</td>
                    </tr>
                    </table>
                    <span class="glyphicon glyphicon-search" aria-hidden="true"></span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component ready.')
        }
    }
</script>