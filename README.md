# AI-Elearning-diagram
<mxfile host="app.diagrams.net">
  <diagram id="sequence-ai-elearning" name="Sequence Diagram AI E-Learning">
    <mxGraphModel dx="1000" dy="1000" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- Lifelines -->
        <mxCell id="2" value="Siswa" style="shape=umlLifeline;" vertex="1" parent="1">
          <mxGeometry x="50" y="50" width="100" height="400" as="geometry"/>
        </mxCell>
        <mxCell id="3" value="Sistem AI" style="shape=umlLifeline;" vertex="1" parent="1">
          <mxGeometry x="200" y="50" width="100" height="400" as="geometry"/>
        </mxCell>
        <mxCell id="4" value="Guru" style="shape=umlLifeline;" vertex="1" parent="1">
          <mxGeometry x="350" y="50" width="100" height="400" as="geometry"/>
        </mxCell>
        <mxCell id="5" value="Admin" style="shape=umlLifeline;" vertex="1" parent="1">
          <mxGeometry x="500" y="50" width="100" height="400" as="geometry"/>
        </mxCell>

        <!-- Messages -->
        <mxCell id="6" value="Login & Akses Materi" style="endArrow=block;" edge="1" parent="1" source="2" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="7" value="Ambil materi dari DB" style="endArrow=block;" edge="1" parent="1" source="3" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="8" value="Tampilkan materi" style="endArrow=block;" edge="1" parent="1" source="3" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="9" value="Ajukan pertanyaan ke chatbot" style="endArrow=block;" edge="1" parent="1" source="2" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="10" value="Proses pertanyaan" style="endArrow=block;" edge="1" parent="1" source="3" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="11" value="Jawaban + rekomendasi" style="endArrow=block;" edge="1" parent="1" source="3" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="12" value="Monitoring hasil belajar" style="endArrow=block;" edge="1" parent="1" source="4" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="13" value="Laporan analisis progres" style="endArrow=block;" edge="1" parent="1" source="3" target="4">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="14" value="Update kurikulum/data" style="endArrow=block;" edge="1" parent="1" source="5" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="15" value="Konfirmasi update" style="endArrow=block;" edge="1" parent="1" source="3" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
