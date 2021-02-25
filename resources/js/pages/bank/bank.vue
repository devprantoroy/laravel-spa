<template>

<div class="card">
  
  <div class="card-header">
      <h3>Bank List <button type="button" class="btn btn-primary float-right"  data-target="#exampleModal">
    Add Bank
  </button></h3>
  </div>
  <div class="card-body">
    
  </div>

  <div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>

</div>
 





 


  
</template>

<script>
import Form from 'vform'
import { mapGetters } from 'vuex'

export default {
  middleware: 'auth',

  metaInfo () {
    return { title: this.$t('Bank') }
  },  

  methods: {
    showmodal () {
      //  this.$emit('#exampleModal').modal('show')
      console.log( this.$emit)
    }
  }

}
</script>
