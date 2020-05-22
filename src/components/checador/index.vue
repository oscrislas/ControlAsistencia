<template>
    <div>
        <b-card
            border-variant="info"
            no-body
            style="max-width: 20rem;"
            img-src="https://placekitten.com/380/200"
            img-alt="Image"
            img-top
        >
            <template v-slot:header>
            <h4 class="mb-0">Hello OScar</h4>
            </template>

            <b-card-body>
            <b-card-sub-title class="mb-2">Presiona para checar</b-card-sub-title>
            <b-card-text>
                <b-button>checa</b-button>
            </b-card-text>
            </b-card-body>

            <b-list-group flush>
            <b-list-group-item>Cras justo odio</b-list-group-item>
            <b-list-group-item>Dapibus ac facilisis in</b-list-group-item>
            <b-list-group-item>Vestibulum at eros</b-list-group-item>
            </b-list-group>

        </b-card>

    </div>
  
</template>

<script>
export default {
    name: 'checador'
}
</script>