.<template>
  <div class="row justify-content-md-center">
    <div class="col-md-6">
      <div class="card">
        <div class="card-header">Ticket - Penugasan Support CC</div>
        <br />
        <div class="card-body">
          <form>
            <div class="form-group row">
              <label for="nomor" class="col-sm-2 col-form-label"
                >No Laporan</label
              >
              <div class="col-sm-10">
                <input
                  type="number"
                  class="form-control"
                  placeholder="Generate by system"
                  readonly
                />
              </div>
            </div>
            <br />
            <div class="form-group row">
              <label for="nomor" class="col-sm-2 col-form-label"
                >Tanggal Laporan</label
              >
              <div class="col-sm-10">
                <input
                  type="date"
                  class="form-control"
                  placeholder="Masukkan tanggal"
                />
              </div>
            </div>
            <br />
            <div class="form-group row">
              <label for="gangguan" class="col-sm-2 col-form-label"
                >Jenis Gangguan</label
              >
              <div class="col-sm-10">
                <select class="form-control">
                  <option>ROIP</option>
                  <option>RDIP</option>
                </select>
              </div>
            </div>
            <br />
            <div class="form-group row">
              <label for="gangguan" class="col-sm-2 col-form-label"
                >Sub Jenis Gangguan</label
              >
              <div class="col-sm-10">
                <select class="form-control">
                  <option>ROIP Command Center</option>
                  <option>RDIP Command Center</option>
                </select>
              </div>
            </div>

            <br />
            <button type="submit" class="btn btn-success float-right">
              Simpan
            </button>
            <button type="submit" class="btn btn-light">Batal</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>