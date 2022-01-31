.<template>
  <div class="pos-f-t">
    <nav class="navbar navbar-dark bg-dark">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarToggleExternalContent"
        aria-controls="navbarToggleExternalContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <ul class="nav-item dropdown">
        <a
          class="nav-link dropdown-toggle"
          href="#"
          id="navbarDropdown"
          role="button"
          data-toggle="dropdown"
          aria-haspopup="true"
          aria-expanded="false"
        >
          User
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </ul>
    </nav>
    <!-- <div class="collapse" id="navbarToggleExternalContent">
    <div class="bg-dark p-4">
      <h5 class="text-white h4">Collapsed content</h5>
      <span class="text-muted">Toggleable via the navbar brand.</span>
    </div>
  </div> -->
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">Ticket Support CC</a>
    </nav>
    <button type="button" class="btn btn-success">Add Tiket</button>
    <table class="table table-bordered">
  <thead>
    <tr>
      <th scope="col">No</th>
      <th scope="col">No Laporan</th>
      <th scope="col">Tgl Laporan</th>
      <th scope="col">Jenis</th>
      <th scope="col">Sub Jenis</th>
      <th scope="col">Petugas</th>
      <th scope="col">Permasalahan</th>
      <th scope="col">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>TS/2/102021/7</td>
      <td>22 Okt 2021</td>
      <td>Komunikasi Seluler</td>
      <td>Pulsa</td>
      <td>Eko</td>
      <td>Removed</td>
      <td>Wo Baru</td>
    </tr>
  </tbody>
</table>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>