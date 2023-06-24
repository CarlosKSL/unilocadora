<template>
    <b-row class="vh-100 vw-100 row-login">
        <b-col sm="5" class="d-flex justify-content-center align-items-center lef-login">
            <div class="col-8">
                <h2>LOGIN</h2>

                <b-form>
                    <b-form-group 
                        label="E-mail"
                        label-for="Senha">
                            <b-form-input 
                            id="email"
                            type="email"
                            placeholder="seuemail@email.com"
                            autocomplete="off"
                        >
                               
                            </b-form-input>
                    </b-form-group>
                </b-form>
            </div>
        </b-col>

        <b-col sm="7"></b-col>
    </b-row>
</template>

<style>

*,
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
}

.row-login {
    margin-left: 0;
}

.left-login {
    background-color: #F2F2F2;
}
</style>