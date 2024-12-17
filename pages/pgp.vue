<template>
  <div class="max-w-4xl px-10 mx-auto space-y-8 text-center">
    <div class="p-4 border border-gray-200 rounded-md">
      <p class="font-semibold">My PGP Key 🔑</p>
      <a href="https://keyserver.ubuntu.com/pks/lookup?op=get&search=0xcf2e26da8d28766be2e0a2975c455988590b6517"
        class="text-blue-500">Download Key</a>
      <br />
      <pre class=" text-left text-white">
        {{ pgpKey }}
        </pre>
    </div>
  </div>
</template>

<script>
//import * as openpgp from 'openpgp';

export default {
  data() {
    return {
      pgpMessage: '',
      validationResult: null,
     
    };
  },
  //old and doesnt work i just left it here bcs maybe i will use it later
  /*
  methods: {
    async validatePgpMessage() {
      try {
        const { data: decrypted } = await openpgp.decrypt({
          message: await openpgp.message.readArmored(this.pgpMessage),
          publicKeys: (await openpgp.key.readArmored(this.pgpKey)).keys,
        });
        this.validationResult = decrypted.data;
      } catch (error) {
        console.error(error);
        this.validationResult = 'Invalid PGP message';
      }
    },
  },
  */
};

</script>
